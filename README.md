## BTC price corrections.

**(I am keeping the code privately. In case you are interested in it, reach me out and let's talk.).**

#### _**Predicting BTC price movements**_

Bitcoin has been one of the trending topics to talk about and specially, within the financial environment. 
Yet, it is a young market with a few number of participants due to the careless of regulations, risk, etc., resulting in a very volatile and manipulated market (under my perspective).

![alt text](https://www.tradingview.com/x/jKWz2hrn/)

Every time a strong hand is operating the the market (low volume of transactions followed by a price spike), price often follows a pattern as a result of the other market participants. That is where I am going to focus and try to predict.

![transactVSpx](https://github.com/aiborra11/BTCmanipulations/blob/master/images/transactions-vs-price.png)

### **Roadmap**

**1. Dataset research:** This point is very important, since BTC price differs in every exchange. In trading a tinny difference might be the difference between profits and loses. 

**2. Dataset creation _(Source)_:** At this point I wrote a pipelines to extract, clean and process all the data I am interested in resulting in a +50 million rows csv file. In order to process it, I had to extract, split and clean the info in different csv to later on concatenate them all in one file. 

**3. Dataset cleaning & engineering _(Source)_:** The most important part of the project. The data I was looking for is not the typical data represented in a candlestick chart, but in the order book. 

![dataset](https://github.com/aiborra11/BTCmanipulations/blob/master/images/dataset.png)

**4. Machine Learning implementation _(Jupyternotebooks)_:** (linear regression, random forest, xgboost, lightgbm). _Due to new evidences I came along the development of the project, I had to modify and adjust new ideas I am still working with._ 

**5. Time Series Forecasting _(Jupyternotebooks)_:** _**Work In Progress**_
