# PIC16B Final Proposal

## Gold Price Prediction Using Machine Learning


## Problem Statement
The gold price has experienced significant fluctuations recently because of the dynamics in geopolitical risks and federal reserves' uncertain rate policies. We want to use machine learning and data analytics to better understand the historical trends behind gold prices and use various features to predict future gold price movements. The model can be applied to support investment decisions or build quantitative trading models in the future. It can also help investors better understand the various factors that contribute to gold price volatility and use the information to make more informed judgments. 


## Project Relevance to Background
This project is closely related to our background in quantitative finance. As mathematics or economics majors, our team had various previous experiences interning in quantitative finance. We want to use our financial knowledge and integrate it with new concepts in PIC 16B to build exciting new machine-learning models to understand the market better. This project is an opportunity to apply class concepts to practice. 


## Data Requirements
We require historical gold price data, such as daily closing and highs and lows over a significant period. This data can be sourced from financial market databases such as Yahoo Finance or Kaggle (For example, Kaggle contains the [monthly gold prices](https://www.kaggle.com/datasets/nhiyen/monthly-gold-price). Since gold prices are influenced by various economic factors, interest rates, inflation rates, and economic growth indicators will be helpful. In addition, the gold price might also be influenced by the overall market and may have a correlation with the price of the S&P 500 or other commodities such as crude oil and silver. Since these datasets can be large, running the model on Google Colab and storing datasets through Google Cloud would be helpful. 


Notably, the data collection involves extensive research into various metrics and data manipulation to combine different datasets and clear them for consistency. We may be unable to access certain datasets for free or have difficulties scraping or obtaining data for the targetted timeframe. We will try to collect as many data categories as possible for a consistent time period and prepare the data for the machine learning model. 


## Summary of Previous Work
Several projects have leveraged machine learning to forecast commodity and cryptocurrency prices. 
- For instance, Abdul Samad Siddiqui from MIT developed a model to predict gold prices using major indices with tools like Curl and Random Forest Regressor, though the model’s accuracy and robustness were not detailed. The project is documented [here](https://github.com/samadpls/GoldPredictAPI/blob/main/README.md).
- Another notable effort by Khadija Korasawala utilized a variety of indicators, including Oil Prices, the S&P 500 index, the Dow Jones Index, US Bond rates (10 years), Euro USD exchange rates, and prices of precious metals such as Silver, Platinum, Palladium, and Rhodium.Additionally, she considered the US Dollar Index and prices of the Eldorado Gold Corporation and Gold Miners ETF from 2011 to 2020. Employing the Random Forest Regressor, her model achieved an 80% accuracy rate in predicting gold prices, detailed [here](https://github.com/4khadija/Gold-Price-Prediction).
- Furthermore, Maggie Ma’s project explored various algorithms to predict cryptocurrency prices. Her approach included Gradient Boosting Regression and Extra Trees Regression, alongside correlation heatmaps to analyze the relationships among several cryptocurrencies like Bitcoin (BTC), Ethereum (ETH), Litecoin (LTC), Bitcoin Cash (BCH), Ripple (XRP), Monero (XMR), and Zcash (ZEC), detailed [here](https://github.com/jieyima/Cryptocurrency_Investment_Analysis_and_Modeling).
We will investigate other machine learning algorithms, including these two, to see if they can be better applied to gold than Random Forest Regression.


## Tools and Skills
Our project would require Python tools such as Pandas for data manipulation, including data quality assessment, data cleaning, etc. Matplotlib and Seaborn are used for data visualization, as we would use a large number of graphs to present our results, and Scikit-learn is used for implementing and evaluating machine learning models, which is the most pivotal part of our project. All these Python packages have been covered during previous lectures. It also requires skills in handling time-series data, performing feature engineering, and model validation. Additionally, the project requires some financial knowledge, including gold trading, asset pricing, and the financial market. 
Learning Objectives
In this project, we would learn Python programming techniques to manipulate and analyze time-series data. Also, we would learn to gain hands-on experience with essential Python libraries like Pandas for data cleaning and transformation, Matplotlib and Seaborn for creating insightful visualizations, and Scikit-learn for building and evaluating various machine learning models. Additionally, I would enhance my understanding of financial indicators relevant to gold trading. Considering our group members' interests and potential career paths, this project fits well and would be a valuable experience for all of us.


### Project Team and Timeline
**Team Members:**
- Jun Liang (Tim)
- Linzhi He
- Michael Thompson

**Timeline:**
- **End of Week 7:** Data collection and processing.
- **End of Week 8:** Test multiple machine learning algorithms.
  - Jun Liang: Random Forest Regression
  - Linzhi Hem: Gradient Boosting Regression
  - Michael Thompson: Extra Trees Regression
- **End of Week 9:** Optimize models and finalize report.
- **Weekend after Week 9:** Final presentation preparations.


