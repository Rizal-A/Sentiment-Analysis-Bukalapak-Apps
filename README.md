# Sentiment Analysis Bukalapak Apps on Google Playstore Reviews
![Sentimen Analysis (2)](https://github.com/Rizal-A/Sentiment-Analysis-Bukalapak-Apps/assets/117552819/fac82481-3ac8-4d01-803b-762fb90c1567)


**This repository is My Final Project in Data Science Dibimbing.Id Bootcamp**. 

## Project Overview

<p><b>Bukalapak</b> is one of the largest e-commerce companies in Indonesia. In 2022 <b>Bukalapak</b> led digital penetration among warungs in Indonesia with a percentage reaching 56%. Then in May 2023, <b>Bukalapak</b> served at least 130 million users and 16.8 million MSME partners, and processed an average of more than two million daily transactions.

  Every e-commerce has its advantages and disadvantages. Usually, the experience of the users of the platform is always expressed in the comment section, be it criticism or satisfaction. This factor usually plays an important role whether the platform is good or not and it can affect the brand growth and quality of the e-commerce platform.
</p>

### Problem Statement
- How customers evaluate Bukalapak application whether it includes positive or negative sentiments
- Knowing the problems that exist on the platform based on negative user reviews
- What strategies can be done by the Bukalapak platform to improve the performance of the application

### Objective

- Knowing the problems faced based on negative user reviews
- Create the best classification model that can predict user sentiment based on existing reviews so that the platform can immediately anticipate and make improvements.
- Provide recommendations to improve the quality and performance of the platform

## Things that are done on this dataset are

- **Data Gathering**

  This Data set was obtained by scraping in Google Playstore
- **Data Understanding and Preprocessing**
  - **Data Cleaning**

    Missing Value & Duplicated Handling
  - **Text Preprocessing**
 
    Using the <b>NLP (Natural Language Processing)</b> method by extracting sentences into smaller words. Below are the steps in text preprocessing
 
    ![Text processing](https://github.com/Rizal-A/Sentiment-Analysis-Bukalapak-Apps/assets/117552819/ab85c5e1-8568-4841-a1f0-255ef84f47ac)

  - **Sentiment Labeling**
    
    Positive Sentiment (Rating 4 - 5) and Negative Sentiment (Rating 1 -3)
- **Exploratory Data Analysis (EDA)**
- **Modeling and Evaluation**

  ![modeling process](https://github.com/Rizal-A/Sentiment-Analysis-Bukalapak-Apps/assets/117552819/13207f51-cda2-4d05-8c52-d29e086a49fc)

- **Deep Dive Negative Sentiment**
- **Business Recommendation**

## Here are the results of Sentiment Analysis

### Best Model for Prediction

**Logistic Regression (F1 Score : 0.868952)**
  - Best Parameter LogisticRegression :  ‘C': 1, 'model__penalty': 'l2', 'solver': 'saga’
  - Best Parameter TFIDF Vectorizer : 'max_features': None, ‘ngram_range': (1, 2)}
    
![best model](https://github.com/Rizal-A/Sentiment-Analysis-Bukalapak-Apps/assets/117552819/c096204d-f743-4bc3-bdea-a7df18708d69)


### Main Business Problem after Deep Dive Negative Sentiment Analysis
- The current application is still not user friendly because there are still customers who experience difficulties and there is no information provided if there are items or products that are removed from the platform for sellers.
- The service provided is still not optimal in handling return or refund problems
- Lack of engagement with customers because the majority of negative sentiments given on average complain about the absence of vouchers or free shipping promos. Even though this can increase engagement with customers

### Business Recommendation
- Periodically evaluate the services and information provided to customers and improve the quality of applications to make them more user friendly
- Provide vouchers or exciting promos according to customer segments to increase engagement and loyalty in using the application.





