# SC_1015_Data_Science
## Introduction
![](http://url/to/img.png](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.grandsierraresort.com%2Factivities%2Fgrand-sierra-cinema&psig=AOvVaw06F4pf19V7AB8BTBqPwgq6&ust=1682334065024000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNC07PTsv_4CFQAAAAAdAAAAABAE)

This is our (A132 Team 6) mini-project for SC1015 Data Science & Artificial Intelligence 2023.
The aim of our project is to create a model that predicts whether a movie will be successful based on certain variables. 

Our measurement of success is **revenue**, which is the most tangible factor that many people base on to evaluate the movies worthiness. 

The dataset we will be using is [**TMDB 5000 Movie Dataset**](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) from [Kaggle](https://www.kaggle.com/).

## Contributors
1. Phan Nguyen
2. Qiang Zhiqin
3. Rachel Phuar 

## Problem statement
1. Is it possible to predict the success of a movie based on pre and post production elements?
2. Which model is best to choose?
Definition of "success" - Generated revenue is higher than budget spent to produce the movie


## Technical Feature

### * Models used
1. Linear Regression
2. Extreme Gradient Boosting (XGBoost)

### * Library/packages
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scipy
6. Sklearn

## Conclusion
+ While a movie's success cannot be attributed solely to either pre-production or post-production elements, a combination of both factors can potentially determine its outcome (Achieving R^2 value of 0.9264 of performing XGBoost on both pre & post-production elements indicates that the output of XGBoost is significantly reliable in predicting the success(revenue) of the movie based on several factors). 
+ This underscores the importance of utilizing both marketing and production resources to create a captivating and appealing movie. 
+ Certainly, a movie's success is influenced by a multitude of factors beyond just pre-production and post-production elements. Some of these factors may include:
  + The quality of the script 
  + The performance of the cast 
  + The skill of the director
  + The effectiveness of the marketing campaign.

## What did we learn from this project?
1. Data Extraction & Cleaning
2. Data Visualisation
3. Uni & Multi Variate Analysis
4. Linear Regression Models
5. XGBoost Algorithm
6. Fine tuning the hyperparameters
7. cosine similarity scores from movie recommendation system

## References
Brownlee, Jason. “How to Remove Outliers for Machine Learning.” Machine Learning Mastery, 18 Aug. 2020, machinelearningmastery.com/how-to-use-statistics-to-identify-outliers-in-data/.

WillKoehrsen. “WillKoehrsen/Data-Analysis.” GitHub, github.com/WillKoehrsen/Data-Analysis/tree/master/random_forest_explained.

Sangeetha, Jame. “Json Parsing & Linear Regression Analysis.” Kaggle, Kaggle, 28 Mar. 2018, www.kaggle.com/sanjames/json-parsing-linear-regression-analysis.

F.koglu, et al. “How Can I Increase the Accuracy of My Linear Regression Model?(Machine Learning with Python).” Stack Overflow, 1 Sept. 1966, stackoverflow.com/questions/47577168/how-can-i-increase-the-accuracy-of-my-linear-regression-modelmachine-learning.

“Sklearn.linear_model.RidgeCV¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html.

“Sklearn.linear_model.RidgeCV¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.linear_model.RidgeCV.html.

“Sklearn.svm.LinearSVR¶.” Scikit, scikit-learn.org/stable/modules/generated/sklearn.svm.LinearSVR.html.

Burak Ergenc,"Predictions with XGboost and Linear Regression", https://www.kaggle.com/code/mburakergenc/predictions-with-xgboost-and-linear-regression/notebook
