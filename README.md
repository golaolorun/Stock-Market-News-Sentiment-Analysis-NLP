# Stock Market News Sentiment Analysis and Summarization
Artificial Intelligence project leveraging Natural Language Processing (NLP) and Sentiment Analysis to analyze stock market news and predict market sentiment.
- by: _Gbenga Olaolorun_

## Description
This project aims to develop a machine learning model that leverages Natural Language Processing (NLP) and Sentiment Analysis to analyze stock market-related news articles. The model will automatically process and categorize news content, providing sentiment summaries at a weekly level. This functionality will empower financial analysts to make more informed investment decisions based on market sentiment.

## Background and Context
The prices of stocks listed on global exchanges, such as NASDAQ, are influenced by various factors, including a company’s financial performance, innovations, and market sentiment. News and media reports can significantly impact investor perceptions and stock prices within the highly competitive financial industry. With the overwhelming volume of news and opinions from diverse sources, investors and analysts often struggle to stay updated and accurately interpret the implications for the market.

To address this challenge, an investment startup seeks to leverage AI-driven sentiment analysis tools to interpret stock-related news and assess its impact on stock prices. By integrating sentiment analysis into their investment strategies, they aim to enhance the accuracy of stock price predictions and improve overall client outcomes.

## Data
The dataset consists of historical daily news articles for a specific company listed under NASDAQ, accompanied by corresponding data on daily stock prices and trade volumes. The dataset includes:

## Data Dictionary
-  Date: The date the news was released
-  News: The content of news articles that could potentially affect the company's stock price
-  Open: The stock price (in $) at the beginning of the day
-  High: The highest stock price (in $) reached during the day
-  Low: The lowest stock price (in $) reached during the day
-  Close: The adjusted stock price (in $) at the end of the day
-  Volume: The number of shares traded during the day
-  Label: The sentiment polarity of the news content
      (1: Positive;
      0: Neutral;
     -1: Negative)

## Objective
-  Build an AI-driven sentiment analysis system to classify stock-related news articles as positive, neutral, or negative.
-  Summarize news articles on a weekly basis to provide insights that correlate with stock price trends.
-  Equip financial analysts with actionable insights to optimize investment decisions.

## Results
- The performance of the sentiment analysis model will be evaluated using metrics such as accuracy, precision, recall, and F1-score. Weekly sentiment summaries will also be generated to help correlate news sentiment with stock price movements.
## Acknowledgements
- My Great Learning for providing the dataset and the problem statement.
