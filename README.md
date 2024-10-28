# Project 15: Demand Forecasting in a Restaurant Chain

## Description
This project aims to predict the demand for different dishes in a restaurant chain, helping to optimize purchase planning and reduce waste.

## Objectives
- Analyze historical sales data for dishes, promotions, and special events.
- Use machine learning models to forecast demand for different dishes.
- Provide insights and recommendations for optimizing restaurant operations.

## Data
The dataset contains simulated sales data from January 2023 to December 2024, including:
- Sales data for three dishes (Dish A, Dish B, Dish C)
- Information about promotions and special events
- Temperature data to account for potential weather-related demand variations

## Methodology
1. **Data Preparation:** Load and preprocess the data, adding relevant features for analysis.
2. **Exploratory Data Analysis:** Analyze sales trends, distributions, and correlations.
3. **Modeling:** Train a RandomForestRegressor model to predict total demand.
4. **Evaluation:** Use metrics like Mean Squared Error (MSE) and R-squared (R²) to evaluate model performance.
5. **Visualization:** Generate visualizations for demand trends and model predictions.

## Results
The model achieved the following performance metrics:
- **Mean Squared Error (MSE):** Measures the average squared difference between predicted and actual values.
- **R-squared (R²):** Indicates the proportion of variance in the dependent variable explained by the model.

## How to Run
1. Ensure all dependencies are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn fpdf nbformat
   ```
2. Run the main script to execute the project:
   ```bash
   python demand_forecasting_project_final_retry_v7.py
   ```

## Recommendations
- Incorporate additional features like holidays and external events for better prediction accuracy.
- Experiment with more advanced models, such as Gradient Boosting or Neural Networks.
- Deploy the model in a production environment for real-time forecasting and decision-making.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- fpdf
- nbformat

