# Amazon Product Sentiment Analysis

This project analyzes customer product reviews from Amazon to explore:
- Which products are most reviewed
- Differences between frequent vs. non-frequent reviewers
- Sentiment of customer reviews

## Dataset
- SQLite file: `database.sqlite` containing Amazon product reviews

## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- SQLite3
- TextBlob for sentiment analysis

## Objectives
- Clean and preprocess review data
- Categorize users by frequency
- Perform sentiment analysis on review summaries
- Visualize patterns in review scores and sentiments

## Key Insights
- Some products have over **500+ reviews**, indicating top-selling items.
- **Frequent reviewers** give more balanced ratings and fewer extreme scores (1 or 5).
- Sentiment analysis shows most reviews are **positive**; common keywords include "delicious", "perfect", and "great".

##  How to Run
1. Ensure `database.sqlite` is in your working directory
2. Open and run `Amazon_Sentiment_Analysis.ipynb`

## Status
Finished 
