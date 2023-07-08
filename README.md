# Stock Market Live Sentiment 

![Image Description](img/SentimentAnalysis.png)

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Website Link](#website-link)
- [Implementation Details](#implementation-details)
    - [Methods Used](#methods-used)
    - [Python Packages Used](#python-packages-used)
- [Steps Followed](#steps-followed)
- [Future Improvements](#future-improvements)

  
## Project Overview
This project focuses on generating an interactive stock sentiment treemap for a portfolio of stocks, using Python. 

## Data Source
This project involves scraping a real-time dataset of stock news, which is updated every 30 minutes, from [FinViz](https://finviz.com), a well-known website for stock screening.

To gather additional information about the stocks, including the Last Closing Price, sector, and industry name, Python is used along with the yfinance library. This library provides the necessary tools and functionalities to retrieve stock data from various sources.

## Website Link

A web-based demonstration of the live stock market sentiment can be accessed from this [link](https://salonijhalani.github.io/live_sentiment.html).

## Implementation Details

### Methods Used
* Data Collection
* Sentiment Analysis
* Data Visualisation

### Python Packages Used
* Pandas
* nltk
* plotly
* yfinance
* BeautifulSoup

## Steps Followed

1. Data Collection: Gathered the food delivery dataset from the provided data source.
2. Data Preprocessing: Performed data cleaning to handle missing values, outliers, and inconsistencies in the dataset. Conducted feature engineering to extract relevant features for the prediction model.
3. Model Development: Utilized regression algorithms to train a food delivery time prediction model. Explored different models such as linear regression, decision trees, random forests, xgboost to identify the best-performing model.
4. Model Evaluation: Evaluated the performance of the models using appropriate metrics such as mean squared error (MSE),root mean squared error (RMSE) and R2 score.
5. Deployment: Deployed the food delivery time prediction model as a standalone application for real-time predictions.

## Future Improvements

Here are some potential areas for future improvements in the project:

* Incorporate more features related to delivery partners, weather conditions, or traffic patterns to enhance prediction accuracy.
* Conduct more comprehensive data analysis to identify additional patterns or correlations that can contribute to better predictions.
* Fine-tune the model parameters to potentially improve performance.
