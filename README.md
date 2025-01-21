# House Pricing Regression Project

## Overview
This project focuses on predicting house prices using a regression model. The dataset used is the **California Housing dataset**, which contains various features such as median income, house age, average number of rooms, and more. The goal is to build a model that can accurately predict the median house value based on these features.

---

## Dataset
The dataset includes the following features:

- **MedInc**: Median income in block group  
- **HouseAge**: Median house age in block group  
- **AveRooms**: Average number of rooms per household  
- **AveBedrms**: Average number of bedrooms per household  
- **Population**: Block group population  
- **AveOccup**: Average number of household members  
- **Latitude**: Block group latitude  
- **Longitude**: Block group longitude  
- **MedHouseVal**: Median house value for households in block group (target variable)  

---

## Project Structure
1. **Data Loading and Exploration**  
   - Load and explore the dataset to understand its structure and characteristics.  

2. **Data Preprocessing**  
   - Handle missing values, duplicates, and prepare the data for modeling.  

3. **Model Building**  
   - Build a regression model using the `LinearRegression` class from `sklearn.linear_model`.  

4. **Model Evaluation**  
   - Evaluate the model using metrics such as:  
     - **Mean Squared Error (MSE)**  
     - **Mean Absolute Error (MAE)**  
     - **R-squared (R²)**  

5. **Visualization**  
   - Create visualizations to understand the data distribution and the model's performance.  
