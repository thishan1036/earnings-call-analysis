# Strategic Intelligence: Tracking Tech Industry Shifts Through Earnings Call Analysis

## Objective
To provide an investment client with actionable intelligence and insight on the strategic direction of major tech players. This analysis answers the critical question: Are market leaders prioritizing future R&D (e.g., 'deep learning') or scaling current infrastructure (e.g., 'data center')? The answer indicates where capital is flowing and which segments are poised for growth.

## Executive Summary 
* **Key Finding 1:** Analysis of 133 transcripts revealed a quantifiable narrative shift from exploratory terms (e.g., 'deep learning') in 2016 to infrastructure-focused terms (e.g., 'data center') in 2020, indicating a market-wide pivot from R&D to implementation.

* **Key Finding 2:** Unsupervised clustering based on phrase similarity successfully segmented companies into distinct strategic groups (Hardware vs. Cloud), providing a data-driven method for competitive landscape analysis.

* **Business Value:** This methodology provides a repeatable, scalable framework for generating quarterly competitive intelligence, allowing stakeholders to anticipate market trends and validate strategic assumptions.

* **Recommendation:** Implement this NLP framework as a quarterly tracking tool to monitor competitors' strategic shifts in real-time. This provides an early warning system for market disruption and informs investment strategy with live, data-driven insights.

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
