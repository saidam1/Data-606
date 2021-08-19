![image](https://bitcoinira.com/wp-content/uploads/2020/10/crypto-price-predictions-1-e1622240319596-1280x720.png)
<p align="center">
   <![image](https://bitcoinira.com/wp-content/uploads/2020/10/crypto-price-predictions-1-e1622240319596-1280x720.png)>
<div align="center">
   <figcaption></figcaption>
</div>
</p>

# Predicting Dogecoin Prices

### By: Saida Muktar


## Table of Content

* Overview
* Goals
* Motivation and Background
* Data
* Software and Packages
* Technical Notebook

## Overview

Cryptocurrency has been a trending topic the past few years, with the most popular coin Bitcoin now being worth almost $40,000. People all over the world have started to put their interest in investing their money into cryptocurrency as it is apparantely "the future". However, there are thousands of coins one can invest in, and how do we actually know which coins are worth our time. 


## Goals

* Can we accurately predict the future price of DogeCoin using different time series prediction models?
* How much influence does social media have on the price of DogeCoin?
* Is there a correlation between Dogecoin, Bitcoin, and Etherum?
* How volatile is Dogecoin compared to the well established coins Bitcoin and Etherum?
* If we factor in the sentiment analysis of tweets into our predictiion models would that make our predictions of Doge prices more accurate?


## Motivation & Background

Dogecoin went from being worth less than a penny to 0.318 as of today. But what has been bringing so much attention to these meme coin, and should Doge be a coin to invest in?

Elon Musk, started tweeting and paying attention to Doge, early January 2021. With simply tweeting he was able to get Doge to a high of 0.7 cents. After Musk's appearance during Saturday Night Live however, Doge's value started to drastically decrease. 


## Data

This report will be using the historic data of Bitcoin, Ethereum, and Dogecoin from Yahoo Finance (https://finance.yahoo.com/).
![bitcoin](https://user-images.githubusercontent.com/70491460/127417939-beda0a49-30b4-494f-9680-442fe67ca68f.PNG)
![doge coin](https://user-images.githubusercontent.com/70491460/127418138-b55dcda2-b17c-491c-a86e-e22e6ff7ec9f.PNG)
![etherum](https://user-images.githubusercontent.com/70491460/127418148-c306774b-d935-40a6-ad9a-cc6bc60e38c1.PNG)
This report will also being using Twitter data on Dogecoin.

## Explaratory Data Analysis
![doge coin o,c,h,l](https://user-images.githubusercontent.com/70491460/127418137-7ae26f7f-35cd-44a9-b503-e2e954628e63.PNG)
![doge eth bit stock prices](https://user-images.githubusercontent.com/70491460/127418139-547e810d-6470-4e41-9af7-d60c33ec20c5.PNG)
![correlation stock prices open](https://user-images.githubusercontent.com/70491460/127418158-c0ddb5ad-2ba2-4df0-a840-0a8a2f9c9576.png)



## Models Implemented
![decision tree](https://user-images.githubusercontent.com/70491460/127418134-701ead9e-c2d9-40bc-a22c-03ed742c725c.png)
![linear regression](https://user-images.githubusercontent.com/70491460/127418151-0ecd4ebf-c49a-45bd-a8c6-97513c68f04e.png)
![SVR MODEL](https://user-images.githubusercontent.com/70491460/127418154-0f289344-0185-4bfb-9380-73521c6235c8.png)
![random forest regression](https://user-images.githubusercontent.com/70491460/127418153-4d89ef3e-2e41-41ff-89cc-ef369341711c.png)

## Sentiment Analysis of Twitter Data on Dogecoin, Bitcoin, and Etherum
### Dogecoin Sentiment Analysis

### Bitcoin Sentiment Analysis

![sentiment scatter plot bitcoin](https://user-images.githubusercontent.com/70491460/130152193-c1f85ff9-6e8b-41f9-93d6-43d78eca642c.png)

![sentiment bar graph bitcoin](https://user-images.githubusercontent.com/70491460/130152092-3dc5f413-39b1-463a-b7f5-ecd3eb95036f.png)

### Ethereum Sentiment Analysis

![eth scatter plot sentiment](https://user-images.githubusercontent.com/70491460/130152428-ba98ab5d-756f-498b-bf2b-3d2e3e135aee.png)

![eth bar plot sentiemtn](https://user-images.githubusercontent.com/70491460/130152433-525a9cde-1a1e-4077-b1c2-f42dae4ea264.png)

## Conclusion

#### Best Model for predicting Dogecoin prices

![decision tree](https://user-images.githubusercontent.com/70491460/127418134-701ead9e-c2d9-40bc-a22c-03ed742c725c.png)





