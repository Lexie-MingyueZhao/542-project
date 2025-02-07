---
editor_options: 
  markdown: 
    wrap: sentence
---

## Project Overview

This repository contains Jupyter Notebooks developed as part of the **DATA 542 Project**.
The project explores ChatGPT interactions in GitHub issues and pull requests using the **DevGPT dataset**.
The analysis focuses on classifying developer issues, understanding interaction patterns, and evaluating sentiment in ChatGPT-generated responses.

## Dataset

The dataset is sourced from **DevGPT**, which contains developer interactions with ChatGPT.
It can be accessed via: - GitHub: [DevGPT Repository](https://github.com/NAIST-SE/DevGPT) - Zenodo: [DevGPT Zenodo Record](https://zenodo.org/records/8304091)

## Research Questions

This project explores the following research questions: 1.
What types of issues (bugs, feature requests, theoretical questions, etc.) do developers most commonly present to ChatGPT?
2.
Can we identify patterns in the prompts developers use when interacting with ChatGPT, and do these patterns correlate with the success of issue resolution?
3.
How does sentiment vary in ChatGPT responses across different types of developer requests?

## Requirements

Ensure you have the necessary dependencies installed before running the notebooks:

``` bash
pip install pandas nltk textblob altair matplotlib
```

## File Descriptions

### `542project-Q1+Q2.ipynb`

-   Loads and preprocesses GitHub issue data from JSON files.
-   Cleans text data using tokenization, lemmatization, and stopword removal.
-   Classifies GitHub issues and explores developer interaction patterns.
-   Uses pandas and matplotlib for data visualization.

### `SentimentAnalysisPullvsIssues.ipynb`

-   Loads and normalizes pull request and issue datasets.
-   Extracts first and last prompts from ChatGPT conversations.
-   Conducts sentiment analysis using `TextBlob`.
-   Visualizes sentiment trends using `Altair`.

## Methodology

1.  **Data Collection & Preprocessing:** The dataset is loaded from JSON/CSV files, and text cleaning techniques are applied.
2.  **Exploratory Data Analysis:** Patterns in developer queries and ChatGPT responses are analyzed.
3.  **Sentiment Analysis:** Using NLP techniques, we evaluate the emotional tone of ChatGPT interactions.

------------------------------------------------------------------------
