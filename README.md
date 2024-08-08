

# Credit Rating Migration

## Overview

This project investigates the impact of adverse news on credit rating changes for S&P 500 companies. By analyzing data from Bloomberg Terminal and a custom Google Search API, we aim to determine if negative news events correlate with movements in credit ratings.

## Data Sources

- **Credit Ratings Data:** Monthly S&P credit ratings for S&P 500 companies (File: `ratings_raw_data.csv`).
- **Adverse News Data:** Retrieved using a custom Google Search API, analyzed for sentiment using FinBERT.

## Key Steps

1. **Data Extraction:** Gathered and merged credit ratings and news data.
2. **Sentiment Analysis:** Classified news articles into positive, negative, or neutral using FinBERT.
3. **Data Preparation:** Cleaned data, mapped ratings to numerical values, and created migration indicators.

## Key Findings

- **Sensitivity of High Ratings:** High credit ratings (e.g., AA+) show more predictable migration trends.
- **Rating Improvement:** Any kind of news - positive, negative or neutral - does not correlate with a credit rating improvement.
- **FinBERT Performance** FinBERT does a good job on classifying the positive news. None of the instances of a positive classification lead to a credit rating deterioration.

## Future Work

- Expand the dataset and timeframe.
- Use more extensive API options for news extraction.
- Integrate additional sentiment analysis tools.

For detailed analysis and methodology, refer to the [project documentation](link-to-detailed-documentation).

