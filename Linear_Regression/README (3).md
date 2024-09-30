# Linear-Regression- Sales Analysis and Prediction Project

## Overview
This project focuses on analyzing sales data and building a predictive model using linear regression. The aim is to identify key factors affecting sales and forecast future sales performance based on historical data. 

## Technologies Used
- Python 3.x
- Libraries: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Data Description
The dataset consists of sales information from a company, including the following features:
- `Units Sold`: The number of units sold.
- `Manufacturing Price`: The cost of manufacturing the product.
- `Sale Price`: The price at which the product is sold.
- `Gross Sales`: Total sales revenue.
- `COGS`: Cost of Goods Sold.
- `Profit`: The profit earned from sales.
- `Sales`: The final sales value.
- `Segment`: The segment of the market (e.g., Government, Midmarket, etc.).
- `Date`: The date of the transaction.

## Key Findings
- A correlation analysis was performed to determine the relationships between different features and sales.
- Visualizations were created to understand sales trends over time and by different market segments.


## Model Implementation
1. **Data Cleaning**: The dataset was cleaned by removing missing values.
2. **Data Splitting**: The data was split into training and testing sets.
3. **Model Training**: A linear regression model was trained on the scaled training data.
4. **Evaluation**: The model's performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Usage
To run this project, ensure you have Python and the required libraries installed. You can clone this repository and run the Jupyter notebook provided.

```bash
git clone https://github.com/daniellabohman/Linear-Regression.git
cd Linear-Regression
