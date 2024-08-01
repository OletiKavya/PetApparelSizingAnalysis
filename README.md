# 🐾 Pet Apparel Sizing Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OletiKavya/PetApparelSizingAnalysis/blob/main/PetApparel.ipynb)

## 📚 Overview

This project analyzes Amazon customer reviews for pet apparel and accessories, focusing on sizing issues. Our goal is to understand how sizing problems affect customer satisfaction and return rates. The analysis includes sentiment analysis, sizing issue classification, and trend analysis to provide actionable insights for improving sizing accuracy in the pet apparel industry.

## 📊 Dataset

- **Source**: [Amazon Reviews 2023](https://amazon-reviews-2023.github.io/)
- **Date Range**: May 1996 to September 2023
- **Categories**:
  - 🐕 Pet Supplies > Dog Supplies > Dog Clothing & Accessories
  - 🐕 Pet Supplies > Dog Supplies > Dog Collars, Harnesses & Leashes

## ⚙️ Setup

To run this analysis, install the following Python libraries:

## 🛠️ Data Preprocessing

1. **Load Data**: Read the dataset from a CSV file and inspect its structure.
2. **Clean Text**: Remove special characters, convert text to lowercase, tokenize, and apply stemming.
3. **Feature Extraction**: Extract product types and classify sizing issues from reviews.

## 🔍 Analysis

### Sentiment Analysis
- **Objective**: Determine the sentiment (positive/negative) of reviews related to sizing issues.
- **Method**: TextBlob is used to analyze the sentiment of cleaned review texts.

### Sizing Issue Classification
- **Objective**: Classify reviews based on common sizing issues (e.g., too small, too large, inconsistent sizing).
- **Method**: A custom classification system is developed using keyword matching.

### Trend and Correlation Analysis
- **Objective**: Examine trends in sizing issues over time and their impact on return rates and customer dissatisfaction.
- **Method**: Visualize trends and analyze correlations between sizing issues and review sentiments.

## 📈 Visualizations

- 📅 **Distribution of Reviews Over Time**: Bar chart showing the number of reviews per year.
- 📊 **Sentiment Distribution**: Bar and pie charts depicting the sentiment of reviews.
- 🛍️ **Common Product Types with Sizing Issues**: Bar chart showing the frequency of sizing issues by product type.
- ⭐ **Impact of Sizing Issues on Ratings**: Bar plot comparing average ratings for reviews with and without sizing issues.
- 📉 **Trend of Sizing Issues**: Line plot showing the percentage of reviews with sizing issues over time.
