# Earnings Call Analysis

## Project Objective
This project uses text mining and sentiment analysis to analyze a corpus of 133 earnings call transcripts from seven major technology companies between 2016 and 2020. The goal is to uncover hidden trends in management language, quantify sentiment shifts, and identify emerging strategic themes across the market.

## Key Findings & Conclusion
* **Shift in Strategic Focus:** The analysis revealed a distinct narrative shift over the 5-year period. Communication in 2016 was heavy with exploratory, conceptual terms like "deep learning," while communication in 2020 shifted towards concrete, infrastructure-focused terms like "data center". This suggests a strategic move from communicating AI's potential to executing on its infrastructural requirements.

* **Successful Business Model Clustering:** Using text clustering, the analysis grouped the seven companies into three distinct and logical business segments based purely on their language: a Hardware-focused cluster (AMD, NVDA, AAPL), a specialized equipment supplier (ASML), and a Cloud/Platform cluster (MSFT, GOOGL, AMZN).

* **Conclusion:** The language used in earnings calls is a rich source of data for tracking corporate strategy. The findings suggest that different segments of the tech industry use technical buzzwords in unique ways, likely tied to their specific business models and marketing objectives.

## View the Full Report
[**Click here to view the complete rendered report**](./earningsCallAnalysis.md)

## Technology Stack & Methods
* **Language/Libraries:** R, readtext, tm (Text Mining), data.table, tidytext, wordcloud
* **Techniques:**
  * Corpus Creation & Text Cleaning
  * Sentiment Analysis (AFINN lexicon)
  * Term-Document Matrix Construction
  * Word Clouds & Phrase Mining
  * Unsupervised Clustering

## Setup & How to Run
1. Clone the repository to your local machine.
2. Ensure you have R and RStudio installed, along with the required libraries listed in the 'Technology Stack' section.
3. The corpus of 133 earnings call transcripts is included in the 'data' folder, making the project self-contained.
4. Open the 'earningsCallAnalysis.Rmd' file in RStudio.
4. To reproduce the final report ('earningsCallAnalysis.md'), you can click the 'Knit' button within RStudio.

## Data Sources
* The corpus of 133 earnings call transcripts was sourced from the ["Earnings Call Transcripts - NASDAQ - 2016-2020"](https://www.kaggle.com/datasets/ashwinm500/earnings-call-transcripts) on Kaggle.