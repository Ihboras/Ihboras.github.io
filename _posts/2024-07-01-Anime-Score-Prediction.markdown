---
layout: default
modal-id: 1
date: 2024-07-01
img: Anime Logo.png
alt: A collage of anime characters used as a logo
description: >
  This project aims to predict target variable anime "Score" from features using various machine learning models.
  This project explores the prediction of anime "Scores" using a dataset from https://myanimelist.net/, 
  which was uploaded to Kaggle. The dataset includes various features about anime, such as genres, episodes, ratings, and more. 
    Multiple Regression Models were tested, including:
    **Linear Regression**: A basic model to establish a baseline.
    **Ridge Regression**: A regularized linear model to handle multicollinearity.
    **Lasso Regression**: A model that performs feature selection by driving some coefficients to zero.
    **Gradient Boosting Regressor**: An ensemble model that builds multiple trees to minimize prediction errors.
  The models were evaluated based on the Root Mean Squared Error (RMSE) on a test set. Feature importance was also analyzed for tree-based models 
  like Gradient Boosting.
  The Gradient Boosting Regressor provided the best predictive performance, effectively handling non-linear relationships between features and the "Score." 
  Ridge and Lasso regression models were also effective, with Lasso offering the additional benefit of feature selection.
link: https://colab.research.google.com/gist/Ihboras/3b4e6f75a97de2dae59f7a63cbb0975c/anime-score-prediction.ipynb
---
