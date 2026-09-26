# Sentiment Analysis on Stock Market News - all-data.csv

## Overview
This project performs Exploratory Data Analysis (EDA) on financial news headlines to understand sentiment distribution (Positive, Negative, Neutral) and text patterns.

Dataset: `all-data.csv` - Contains 2 columns (Sentiment, Text) with 4840+ financial news sentences.

## Tech Stack Used
- Python
- pandas - Data loading and cleaning
- numpy - Numerical operations
- matplotlib - Plotting
- seaborn - Advanced visualizations

## Steps Performed
1.  **Data Loading:** Loaded CSV file without header and assigned columns `Sentiment` and `Text`.
2.  **EDA:** Checked shape, value_counts for sentiment distribution.
3.  **Text Length Analysis:** Calculated word count per headline to compare sentiment vs length.
4.  **Visualizations:**
    - Countplot for Sentiment Distribution
    - Boxplot for Text Length by Sentiment
    - Barplot for Average Words by Sentiment
5.  **Insights:**
    - Most headlines are Neutral followed by Positive.
    - Negative headlines tend to be slightly longer.
    - Average text length is 20-25 words.

## Visualizations
- Sentiment Distribution (Countplot)
- Text Length Boxplot
- Average Words Bar Chart

## Key Findings
- Neutral sentiment dominates the dataset (approx 60%).
- Financial news uses moderate length sentences.
- This EDA can be used before building a sentiment classification model.

## How to Run
1. Upload `all-data.csv` to Colab
2. Run the 6 code blocks provided
3. Save graphs and upload to GitHub

## Author
OIBSIP Data Analytics Internship - Level 2 Task
