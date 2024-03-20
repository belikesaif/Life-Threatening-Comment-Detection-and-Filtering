---
title: Life-Threatening Comment Detection and Filtering
author: Saif-Ur-Rehman
date: 2024-03-21
tags: NLP, Sentiment Analysis, Text Classification, Python
---

# Life-Threatening Comment Detection and Filtering

## Description

This project aims to develop a Python script for detecting and filtering life-threatening comments from a dataset of social media comments. The script utilizes Natural Language Processing (NLP) techniques, including sentiment analysis, to identify comments with negative sentiment and containing language indicative of life-threatening behavior.

## Project Overview

Social media platforms often face challenges in managing harmful content, including comments that contain threats of violence or harm to individuals. Automatic detection and filtering of such comments are essential for maintaining a safe online environment.

In this project, we employ the following steps:

1. **Data Preprocessing**: The comments are preprocessed to remove non-alphanumeric characters and converted to lowercase for uniformity.

2. **Sentiment Analysis**: We use NLTK's SentimentIntensityAnalyzer to analyze the sentiment of each comment. Comments with negative sentiment are considered for further analysis.

3. **Keyword Matching**: We identify comments containing keywords associated with life-threatening behavior, such as "kill", "murder", "bomb", etc.

4. **Filtering**: Comments meeting both the negative sentiment and keyword matching criteria are filtered out as potential life-threatening comments.

5. **Output**: The filtered comments are saved to a new CSV file for further analysis or moderation.

## Tools Used

- Python: Programming language used for script development.
- NLTK: Natural Language Toolkit library for sentiment analysis.
- Pandas: Library for data manipulation and handling CSV files.
- Google Colab: Online platform for running Python scripts collaboratively.

## Dataset

The dataset used in this project consists of social media comments scrapped from various platforms using Google API client. The comments include opinions, threats, and discussions that may contain life-threatening language.

## Instructions

1. Upload the 'ThreatsComments.csv' file containing social media comments to your Google Colab environment.
2. Execute the provided Python script to detect and filter life-threatening comments.
3. View the output CSV file 'FilteredLifeThreatComments.csv' containing the filtered comments.

Feel free to customize and extend the script as needed for your specific use case or dataset.

Let's get started!
