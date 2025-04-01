# Weather Prediction Project: Daily Rainfall Forecasting

This project focuses on building a machine learning model to predict the occurrence of rainfall for each day of the year. The prediction task is framed as a binary classification problem, where the model determines the probability of rainfall on a given day based on meteorological features.

## Project Background

Developed as part of the Kaggle Playground Series Season 5, Episode 3 competition
Competition link: https://www.kaggle.com/competitions/playground-series-s5e3/overview

Technical Details

Objective: Predict the likelihood of rainfall on a daily basis
Evaluation Metric: Area Under the ROC Curve (AUC-ROC)

The model generates probability scores for rainfall, which are then evaluated against actual observations using the ROC curve methodology. This approach rewards models that can effectively rank-order instances by their likelihood of rainfall, even if the absolute probability calibration isn't perfect.
 
