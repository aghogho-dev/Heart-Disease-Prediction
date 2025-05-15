# Overview

I want to explore the best model that maximizes AUC for the Heart Prediction Dataset.

{Provide a description of the data set that you are analyzing.  Include the link of where you obtained the data.}
The [dataset](https://www.kaggle.com/competitions/heart-disease-prediction-dataquest/data) contains 11 columns and the target `HeartDisease`. 

{Describe your purpose for writing this software to analyze the data.}
I want to develop a method to approach future Data Science projects.


# Data Analysis Results

{List the questions and the answers you found by doing this analysis.}
Which is the best model? 
The Top3 model from optimizing with Optuna when combined with a VotingClassifier

What does EDA tell you about the data? 
- There is no single feature that can perfectly predict the outcome.
- Some numerical feature contains outliers and may need to be transformed


# Development Environment

{Describe the tools that you used to develop the software}
Virtual Environment, Python, Jupyter Notebook, Git, GitHub

{Describe the programming language that you used and any libraries.}
Python, Pandas, Numpy, Scipy, Scikit-Learn, XGBoost, Optuna.
The full list of packagesc can be found in `requirements.txt`
