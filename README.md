# StockMarket_SentimentAnalysis

## Introduction 
Individuals and institutions can purchase and sell shares or ownership holdings in publicly listed corporations on the stock market, which is a financial marketplace. It is sometimes referred to as the stock exchange or equity market. The main goal of the stock market is to make it easier for people to purchase and sell stocks, which enables businesses to obtain cash and gives investors the chance to profit from those businesses' success.
Shares, or stocks: Shares are ownership interests in a firm. A percentage of a firm's assets and profits are yours to claim when you buy stock in the company. Businesses can generate money by issuing stocks for a variety of reasons, including growing their business or funding new initiatives.
The stock market is a dynamic, ever-evolving phenomenon that is impacted by public opinion as well as economic facts. Accurately predicting the movements of the stock market has never been an easy task. It entails sorting through enormous amounts of data, comprehending the subtleties of market psychology, and making wise choices in a very unstable setting.
Stock market predictions are forecasts or estimates on the future direction of stock prices and general market trends that are made by analysts, investors, or financial specialists. Based on a variety of variables and analytical methods, these forecasts make an effort to determine whether stock prices will grow (bullish), decline (bearish), or stay mostly unchanged.
The attitude and general mood of traders and investors is known as market sentiment, and it can have an impact on predictions. Bullish forecasts can originate from positive sentiment, whilst bearish predictions might stem from negative sentiment.
Sentiment analysis, often referred to as opinion mining, is a natural language processing (NLP) approach wherein the sentiment or emotional tone indicated in a textual document—such as a news story, review, tweet, or comment—is identified and extracted. 

Determining if and to what extent a text reflects a good, negative, or neutral attitude is the aim of sentiment analysis. It is extensively employed in many different applications, such as market research, customer feedback analysis, and social media monitoring.

**Sentiment Analysis:** Sentiment analysis often involves grouping text into several sentiment categories. The most common groupings are:
1. Positive: Indicates a positive emotion, such as approval, enjoyment, or contentment.
2. Negative: Expresses an undesirable feeling, such anger, sadness, or unhappiness.
3. Neutral: This term indicates a lack of significant positive or negative emotion and is typically used to describe objective or factual data.
The objective is to ascertain if people's sentiments on a particular stock or the market at large are favourable, negative, or neutral. Sentiment analysis algorithms employ language analysis, machine learning, and lexicon-based approaches to interpret sentiment. Understanding traders’ and investors’ overall attitude can provide valuable clues into future market movements.

## About Dataset:
**Dataset Information:**
The tweets in the dataset are associated with the top 25 stock tickers on Yahoo Finance in terms of viewership.For the period of September 30, 2022, to September 30, 2021, data is being gathered.
The collection also contains price and volume information from the stock market that is related to the stocks and dates that are referenced in the tweets.

**Dataset Description:**

<u><i>Dataset 1:</i></u>

- Date: The time and date of each tweet's posting are noted in this column.
- Tweet: Each tweet's whole content is included in this column.
- Stock Name: The whole stock ticker name for which the tweet was gathered is provided in this column.
- Company Name: The whole name of the business linked to the specified stock ticker is provided in this column.

<u><i>Dataset 2:</i><u>

- Date: The date when the stock market data was seen or recorded is represented by this attribute. It is a list of the dates on which every data point was gathered. Time series analysis requires dates in order to monitor the evolution of financial variables such as stock prices.
- Open: The price of a stock at the start of a trading session or the opening of the market on a specific day is referred to as the "Open" price. It is the price at which the market opened for that trading day's first transaction.
- High: During a trading session on a certain day, the "High" price denotes the highest price at which the stock was traded. It displays the highest value attained on that particular trading day.
- Low: The lowest price at which the stock was traded during the same trading session is indicated by the "Low" price, on the other hand. It is the lowest price the stock fell to that day.
- Close: The price listed as "Close" represents the stock's closing price at the conclusion of the trading day or when the market closes. It is the final price that was noted prior to the market closing.
- Adj Close (Adjusted Close): The closing price after adjustments for things like stock splits, dividends, and other business activities is known as the "Adj Close" price. When compared to historical data, it offers a more accurate depiction of the stock's worth over time.
- Volume: During a trading session on a particular day, the "Volume" feature shows the total number of shares or contracts exchanged. It displays the stock's trading activity and liquidity. A high trade volume may be a sign of rising volatility or investor interest.
- Stock Name: The name or ticker symbol of the particular stock or financial instrument under observation is usually included in this section. When a dataset includes data on several stocks, it is utilized to distinguish between them.

## Methodology
**Time Series Analysis**
A statistical and mathematical method for examining and analyzing data that is gathered or recorded across a succession of discrete time intervals is called time series analysis. It entails taking measurements, observations, or data points at uniformly spaced intervals and modelling and analyzing them. Numerous disciplines, including finance, economics, environmental science, engineering, and more, frequently use time series data.

**GANs, or Generative Adversarial Networks:**
In 2014, Ian Goodfellow and associates proposed a type of machine learning models known as Generative Adversarial Networks, or GANs.
Two neural networks, each having a distinct function, make up a GAN:
- Generator: The main job of the generator network is to create new data samples that are similar to an existing dataset. With random noise as input, it generates data samples that should be identical to the original data. Over time, the generator is educated to become more adept at producing data that is more realistic.
- Discriminator: This network serves as an adjudicator. Its task is to distinguish between fictitious data samples produced by the generator and actual data samples taken from the training dataset. The discriminator is taught to improve its ability to discern between authentic and fraudulent data.

Generating realistic pictures, videos, or text has been the traditional usage of GANs; however, these days, they are also being employed in finance, more notably in stock price prediction.
GANs are used to create artificial yet incredibly realistic stock price data in the context of stock prediction. They are made up of a discriminator and a generator neural network. 
The discriminator assesses the legitimacy of the generated synthetic stock price data by comparing it with actual market data. The generator is always motivated to increase its accuracy by this adversarial process.

> [!NOTE] 
> The secret to GANs' success in stock prediction is their capacity to identify intricate patterns and trends in stock price data, even in extremely erratic markets. GANs may provide future pricing scenarios by being trained on past price data, which improves predicting accuracy.


