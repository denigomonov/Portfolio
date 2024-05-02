# Portfolio
Denis Gomonov's Data Science Portfolio

# Goal (2024): Practical Application of NLP/Comp Vision

# Project (2024) (unreleased): Political Database + Context Summarization 
* Led team of 4 to build a political database SaaS platform as a subscription service
* Collected data from multiple gov entities via API calls such as: congress.gov, pa.gov, data.gov, etc
* Built out a platform with the latest techniques using Next.js, Tailwind, httpx, clerk, etc
* Provided research on data licensing, legal matters and service costs

_snippet from the website + nlp work:_

<img src="https://github.com/denigomonov/Portfolio/assets/34199193/5c3fb35c-6eee-458f-bad2-c3d8ad2a5eaa" width="700">


# [Project (2023): Insurance Claim Fraud Analysis](https://github.com/denigomonov/Fraud-Analysis)
* Analyzed and created visualizations to explore trends showing distinct features that lead to fraudulent claims
* Prepared and transforemd data via categorical encoding to be fit for Keras model, acquired from [Kaggle](https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection)
* Built a model with 32 input neurons in the input layer, 32 neurons in 1 hidden layer and final dense layer utilizing binary-crossentropy loss and adam optimizer, resulting in loss: 0.9092 - accuracy: 0.9361 on test data

_snippet from Notebook:_

![Animation](https://user-images.githubusercontent.com/34199193/212479727-a3ae6226-b6e6-44fe-9ace-4dba4669c53f.gif)


# [Project (2022): BlackRock Hackathon Digital Asset and Crypto Tracking ETF Research Hub](https://github.com/denigomonov/BLKHACK22)
* Analyzed and transformed BTC datasets to exclude bot entries and show parallel data between Twitter entries & market ticker prices
* Optimized string data by removing stop words and stemming, further calculating sentiment scores via subjectivity, polarity, vader metrics
* Created 3 demo hourly visualizations with scaled vader sentiment scores against BTC volume, BTC USD, BTC close price 


# [Project (2021): Netflix Trading Strategy](https://github.com/denigomonov/Streaming-Services-Trading-Strategy)
* Prepared the NFLX data for visual portfolio analysis by calculating relevant metrics such as SMA, EMA, ROC, RSI, Bollinger Bands, etc
* Created dynamic _Candlestick_ and _RSI_ plots for detailed analysis of stock perfomance via Plotly
* Established a buy/sell signal and prepared a list of classification algorithms with performance comparisson via _k_-fold cross validation
* Determined Random Forest to be the best applicable model, achieving classification accuracy score of 0.91 by tuning with GridSearchCV 

### [For More Details](https://github.com/denigomonov/Streaming-Services-Trading-Strategy#readme)

_snippet from Notebook:_

<img src="https://user-images.githubusercontent.com/34199193/123129154-bae87700-d419-11eb-854a-0ef14755cca6.gif">


# [Project (2020): COVID-19 U.S. Dashboard](https://github.com/denigomonov/COVID19-Dash)
* Created _EDA & external_ dynamic dashboard breaking down the spread of Covid-19 in U.S. using Python in Jupyter & Atom
* Prepared and transformed data read from [USAFACTS](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)
* Optimized OLS Regression for Covid-19 Case & Death 2-Week predictions
* Engineered features and built custom plots for metric analysis, geo-mapping and forecasting via Plotly
* Launched _external_ dynamic dashboard on Heroku

### [For More Details](https://github.com/denigomonov/COVID19-Dash/blob/master/README.md)

_Heroku App GIF:_

<img src="https://user-images.githubusercontent.com/34199193/89723538-d5625f00-d9c5-11ea-9243-4aa8f7dc824c.gif">

# [Project (2020): Advanced Iris Species EDA](https://github.com/denigomonov/Iris-EDA)
* Created EDA-Notebook producing uncommon visualization techniques for Iris Species using Python & Jupyter
* Explored _petal & sepal_ features with customized Scatter, Coordinates and Categorical-Coordinates plots
* Determined features and applied K-Nearest-Neighbors classification with best model fit & performance via Scikit-learn
* Visualized KNN-algorithm output and its decision boundary in 2D format with Countour plot

### [For More Details](https://github.com/denigomonov/Iris-EDA)

_snippet from Notebook:_

<img src="https://user-images.githubusercontent.com/34199193/89725192-f1243000-d9da-11ea-913b-3dd6b3f2c8e9.gif">

# [Project (2019): Airbnb in New York City EDA](https://github.com/denigomonov/Airbnb-NYC-EDA)
* Created EDA-Notebook exploring how Airbnb is affecting neighbourhoods of NYC using Python & Jupyter
* Collected data from [Inside Airbnb](http://insideairbnb.com/) and maintained it on Kaggle with achieving _Top-20 Most Voted, 1850+ Votes, Gold medal_
* Analysed and visualized distribution of prices of New York City boroughs & neighborhoods via Seaborn
* Optimized text data presented and provided with Listing Titles insights on trend terminology 

### [For More Details](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)

_snippet from Kaggle:_

<img src="https://user-images.githubusercontent.com/34199193/89150990-d9a5fc80-d52d-11ea-9cdd-72a498b39e55.png" width="700">
