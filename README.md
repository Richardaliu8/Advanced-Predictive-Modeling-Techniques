# Advanced-Predictive-Modeling-Techniques
Project Overview  
This project focuses on applying advanced machine learning techniques to predict financial metrics from the NYSE dataset and to diagnose breast cancer using the well-known breast cancer dataset. The analysis spans Random Forest and Lasso regression models for stock predictions and a decision tree classifier for medical diagnosis.  

Features  
Random Forest Regression: Implementation of Random Forest models to predict estimated shares outstanding in the NYSE dataset. Includes a comparison of models with default parameters and a variation where the min_samples_split parameter is adjusted.  
Variable Importance Analysis: Utilization of "Mean Decrease in Impurity" and "Permutation Feature Importance" techniques to determine the significance of different predictors within the Random Forest model. Provides a detailed comparison of how each method assesses variable importance.  
Lasso Regression Comparison: Comparison of a Lasso regression model's performance against the Random Forest model using the same training and test dataset splits, highlighting differences in predictive accuracy and model suitability.  
Decision Tree Classification for Medical Diagnosis: Application of a decision tree classifier to the breast cancer dataset, aimed at predicting diagnoses. Includes analysis of model effectiveness through a confusion matrix and discussion on the potential for model pruning.
Visualization and Model Evaluation: Detailed visualization of the decision tree, highlighting critical variables and their roles in diagnosis predictions. Discussion on whether pruning the tree might enhance model performance, including strategies for deciding where and how to prune.  

Purpose  
The purpose of this project is to showcase the application of diverse machine learning methods across different data types and objectives. By tackling both regression in financial contexts and classification in medical diagnostics, the project demonstrates the adaptability and effectiveness of advanced modeling techniques in deriving insights and aiding decision-making in complex scenarios.  
