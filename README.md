# Bitcoin Consensus Analysis

## Project Description
This project centers on Big Data analytics, specifically focusing on sentiment analysis of public opinion towards Bitcoin. A market research company recruited our team to estimate the consensus on Bitcoin by analyzing a vast dataset consisting of several million tweets about Bitcoin. The objective was to perform a sentiment analysis and display daily sentiment variations. Additionally, the project aimed to answer intriguing questions about tweet interactions and their correlation with Bitcoin's value.

## Objective
The primary goal was to leverage Big Data tools and techniques to analyze public sentiment towards Bitcoin, utilizing a large-scale dataset of tweets. The analysis aimed to uncover trends and patterns in sentiment and how these relate to Bitcoin's market value.

## Datasets
- Tweet Dataset: Contained several million tweets mentioning Bitcoin, extracted by a team of data engineers.
- Bitcoin Historical Data: The historical BTC-USD data was sourced independently to examine correlations between sentiment and Bitcoin's value.

## Analysis and Findings
### Sentiment Analysis
Using PySpark, the tweet data was processed and analyzed to perform sentiment analysis. The sentiment of each tweet was categorized as positive or negative . The following steps were taken:

- Data Preprocessing: The tweets were cleaned and preprocessed to remove noise, such as special characters and stop words.
- Sentiment Classification: Sentiment analysis was conducted using natural language processing techniques to classify each tweet.

### Interaction Analysis
Further analysis was performed to answer specific questions:

- Likes on Negative vs. Positive Tweets: It was determined whether negative tweets received more likes compared to positive ones.
- Interactions on Negative vs. Positive Tweets: The number of interactions (replies) on negative tweets was compared to those on positive tweets.

### Additional Analysis
An additional analysis investigated the correlation between sentiment variation and Bitcoin's value fluctuation. Historical BTC-USD data was used to perform this task.

## Tools and Techniques
This project utilized `PySpark` and its various tools to handle and analyze the large-scale tweet dataset. Work was conducted on the cloud using **Databricks Community**.

## Summary
This Big Data project successfully analyzed public sentiment towards Bitcoin using a vast dataset of tweets. By leveraging PySpark, the project provided insights into daily sentiment trends and interactions with tweets, and explored the correlation between sentiment and Bitcoin's market value. The findings contribute to a deeper understanding of public opinion on Bitcoin and its potential impact on market dynamics.
