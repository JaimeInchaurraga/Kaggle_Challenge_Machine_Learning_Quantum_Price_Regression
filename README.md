# Kaggle_Challenge_Machine_Learning_Quantum_Price_Regression


Project Overview

This project was part of the Kaggle competition, "Lo cuántico se nos va de las manos 💰", where the goal was to help Manuel find a reasonably priced conventional computer in a world dominated by quantum computing. Due to his low budget, Manuel needed to avoid being scammed by adjusting prices using a machine learning model. Our objective was to build a model capable of predicting computer prices based on provided features, ensuring that Manuel got the best deal possible.
Competition Description

The task was to create a machine learning model to predict the price of computers, using various features provided in the dataset. The model aimed to minimize the Root Mean Squared Error (RMSE), which was used as the evaluation metric for the competition. RMSE measures the standard deviation of residuals or prediction errors, indicating how well the model's predictions fit the actual data.
Approach

Data Cleaning & Preprocessing:  
Initially, the dataset required cleaning. Handling missing values, ensuring correct data types, and dealing with outliers were crucial steps in ensuring data quality.
I explored various feature engineering techniques to create meaningful features, which could improve model accuracy.  

Exploratory Data Analysis (EDA):  
A comprehensive analysis of the dataset was performed to understand the underlying patterns and distributions. Visualization techniques were used to uncover trends and potential relationships between features and the target variable (price).  

Model Selection:  
Various regression models were evaluated to predict the computer prices. These included:
Linear Regression
Random Forest
Gradient Boosting Machines (GBM)
XGBoost
Hyperparameter tuning was performed to optimize the performance of each model.  

Evaluation:  
The models were evaluated using the RMSE metric on the validation set, and the best-performing model was selected based on the lowest RMSE value.  

Submission:  
The final model was applied to the test dataset, and predictions were submitted to Kaggle.
Results:   
After thorough experimentation and model tuning, the final model achieved a top 6 placement among all competition participants. This was a significant achievement, demonstrating the accuracy and reliability of the model in predicting computer prices.

Key Takeaways:  
- Feature Engineering: Creating meaningful features significantly improved the model's accuracy.
- Model Tuning: Careful hyperparameter tuning and evaluation across multiple models were key to achieving low RMSE scores.
- EDA: Deep exploratory data analysis helped identify important relationships and patterns in the data, which guided the modeling process.
- Evaluation Metric: Root Mean Squared Error (RMSE)


Final Result:  
The model ranked within the top 6 of all submissions, validating the approach taken and its effectiveness in the competition.
