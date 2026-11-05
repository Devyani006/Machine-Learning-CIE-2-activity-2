
# House Price Prediction 

**Unit II** – Supervised Learning: Regression  
**Name**: Devyani Dhokrat  
**Roll No.**: AD3146  

## Project Overview
This repository contains a complete workflow for predicting house prices using the California Housing dataset. It fulfills the requirements for **Activity 2: Simple House Price Prediction** using a Linear Regression machine learning model.

## Dataset
The dataset used is the standard **California Housing Dataset**, which contains information such as median income, house age, average rooms, population, and location coordinates to predict the median house value (`MedHouseVal`).

## Workflow Summary
1. **Data Loading & Inspection**: Loaded the dataset using `scikit-learn` and verified the shape and missing values (no missing values found).
2. **Exploratory Data Analysis (EDA)**: Visualized the distribution of median house values using `seaborn` and `matplotlib`.
3. **Data Splitting**: Separated the data into features (X) and target (y), and split it into an 80% training and 20% testing set.
4. **Model Training**: Trained a `LinearRegression` model on the training set.
5. **Model Evaluation**: Evaluated the model using regression metrics:
   - **MAE** (Mean Absolute Error)
   - **MSE** (Mean Squared Error)
   - **RMSE** (Root Mean Squared Error)
   - **R-squared (R2)**
6. **Visualization**: Created a scatter plot comparing Actual vs. Predicted house prices.
7. **Simulation**: Simulated a real-world prediction by feeding a single unseen house's features into the trained model.

## Files in this Repository
- `House_Price_Prediction.ipynb`: The complete, runnable Google Colab Notebook with all code and outputs.
- `california_housing_dataset.csv`: The dataset extracted and exported for reproducibility.
- `README.md`: This descriptive file.

## How to Run
To test this code, you can open the `.ipynb` file in Google Colab or Jupyter Notebook, ensure the necessary libraries (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`) are installed, and simply "Run All" cells.
