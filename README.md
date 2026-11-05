
# Activity 2: Simple House Price Prediction

**Name**: Devyani Dhokrat  
**Roll No.**: AD3146  

## Activity Description
This repository contains the workflow and model for **Activity 2: Simple House Price Prediction**. The objective of this activity is to build a Linear Regression machine learning model to predict house prices based on various features and evaluate it using standard regression metrics.

## Dataset / Source
The dataset used for this activity is the California Housing dataset, originally published in: Pace, R. Kelley and Ronald Barry, "Sparse Spatial Autoregressions," Statistics and Probability Letters, 33 (1997) 291-297.

## Work Completed
1. **Data Loading & Inspection**: Loaded the dataset and verified there were no missing values.
2. **Exploratory Data Analysis (EDA)**: Visualized the distribution of median house values.
3. **Data Splitting**: Separated features and target, and split the data into 80% training and 20% testing sets.
4. **Model Training**: Trained a `LinearRegression` model on the training data.
5. **Model Evaluation**: Evaluated the model using MAE, MSE, RMSE, and R-squared metrics.
6. **Visualization**: Created a scatter plot comparing actual vs. predicted house prices.
7. **Simulation**: Simulated a real-world prediction on an unseen data point.

## Key Results
The Linear Regression model achieved the following performance on the test set:
- **Mean Absolute Error (MAE)**: ~0.53
- **Mean Squared Error (MSE)**: ~0.56
- **Root Mean Squared Error (RMSE)**: ~0.75
- **R-squared (R2)**: ~0.58

The R-squared value indicates that the model explains approximately 58% of the variance in house prices.

## Acknowledgement
This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129).
