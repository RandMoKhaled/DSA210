# Huda Beauty Shade Inclusivity: Data Science Project

## Overview

This project explores the extent to which Huda Beauty’s claims of shade inclusivity in its complexion product lines (such as foundations and concealers) are supported by customer feedback and reviews. By analyzing user reviews, product shade data, and social media sentiment, we aim to evaluate whether customers with different skin tones experience equal satisfaction, or if gaps exist despite the brand's inclusive marketing.

## Purpose of the Project

The purpose of this project is to assess whether Huda Beauty's product offerings, particularly foundations and concealers, provide shade options that meet the needs of a diverse range of skin tones. We analyze reviews and sentiment data to determine if customers from underrepresented skin tones (e.g., deep/dark) report similar levels of satisfaction as customers with lighter skin tones. This study provides valuable insights into the real-world impact of inclusivity in the beauty industry.

## Motivation

Huda Beauty is a globally recognized makeup brand with a reputation for being highly inclusive, especially in complexion products. The brand's marketing and product claims emphasize diversity, but it's important to assess whether this inclusivity translates to actual customer satisfaction. This project evaluates whether Huda Beauty lives up to its inclusive image by analyzing customer reviews, sentiments, and skin tone-based feedback.

## Data Source

1. **Product and Shade Data**:
   - Collected from Sephora’s and Huda Beauty's websites.
   - Includes product names, number of shades, descriptions, and launch dates for complexion products like foundations and concealers.

2. **Customer Reviews**:
   - Scraped from Sephora, Ulta, and MakeupAlley.
   - Data includes user ratings, text reviews, and mentions of skin tone.

3. **Social Media Data**:
   - Collected tweets containing hashtags like #hudabeauty and #fauxfilterfoundation.
   - Extracted Reddit comments from beauty communities.

4. **Enrichment**:
   - Mapped product shades to generalized skin tone categories (light, medium, dark, deep).
   - Used the Fitzpatrick scale to categorize user descriptions of their skin tone.

## Data Analysis

1. **Preprocessing**:
   - Cleaned review data by removing HTML tags and irrelevant content.
   - Standardized terminology for shades and undertones to facilitate analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of shades per product.
   - Generated word clouds for different skin tone groups to identify common themes in reviews.

3. **Sentiment Analysis**:
   - Analyzed sentiment using VADER and TextBlob libraries to calculate sentiment scores of reviews.
   - Compared average sentiment scores across different skin tone groups.

4. **Hypothesis Testing**:
   - Null Hypothesis (H₀): There is no significant difference in average sentiment between skin tone groups.
   - Applied ANOVA test to validate or reject the hypothesis.

5. **Machine Learning**:
   - Built a logistic regression model to predict the sentiment of reviews (positive/negative) based on features such as skin tone, number of shades, and sentiment keywords.



