# Gold Recovery Prediction Project

## Overview
In collaboration with Zyfra, a company renowned for its efficiency solutions in heavy industry, this project focuses on developing a machine learning model to predict gold recovery from ore. The objective is to optimize production and eliminate unprofitable parameters by accurately forecasting the amount of gold recovered during the extraction and purification processes.

## Description
The primary goal is to create a prototype machine learning model capable of predicting gold recovery from gold ore. The model will utilize historical data on gold extraction and purification to provide valuable insights that can enhance operational efficiency and profitability.

## Objectives
The project will involve three main stages:
1) Data Preparation: Organizing and preprocessing the data to ensure it is suitable for analysis and modeling.
2) Data Analysis: Performing thorough data analysis to understand the underlying patterns and relationships within the data.
3) Model Development and Training: Developing and training a predictive model using advanced machine learning techniques.

The model aims to predict two specific metrics:
- Rougher concentrate recovery (rougher.output.recovery)
- Final concentrate recovery (final.output.recovery)

By accurately forecasting these values, the model will help Zyfra optimize the gold recovery process, improving both efficiency and profitability in their operations.

## Libraries
The project leverages various Python libraries, including:
- `pandas` for data manipulation and analysis
- `matplotlib` for data visualization
- `scikit-learn (sklearn)` for machine learning model development and evaluation

## Conclusion
This project has unveiled crucial insights into the intricate task of predicting gold recovery from ore, shedding light on the multifaceted challenges inherent in the process. Key observations include:
- Disparities in data dimensions among the train, test, and full datasets necessitated meticulous feature selection to ensure model compatibility.
Addressing missing values was a significant preprocessing hurdle, prompting strategies like dropping missing targets and forward filling to maintain data integrity.
- The low Mean Absolute Error (MAE) during the comparison of actual and predicted recovery values in the training dataset highlighted the precision of the actual values derived.
- The absence of certain features linked to ore mining outputs in the test dataset posed challenges for model evaluation and prediction.
- Analysis of metal concentration trends throughout the purification process provided valuable operational insights.
- Consistency in particle feed size distributions between the train and test datasets assured robustness in model training and evaluation.

The development and evaluation of various regression models, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor, yielded promising results. Among these models, the Linear Regression model was preferred for its balanced performance in terms of accuracy and computational efficiency, achieving a satisfactory Symmetric Mean Absolute Percentage Error (SMAPE) score of 9.97% on unseen data, indicating its capability to predict gold recovery targets with approximately 90% accuracy.

Looking ahead, continual refinement of models and strategies based on real-world feedback will be pivotal in further enhancing predictive accuracy and operational efficiency in gold recovery processes. Embracing a dynamic approach to model development and deployment will enable the seamless integration of cutting-edge technologies into industrial practices, driving continuous improvement and innovation in the field of ore mining and processing.

