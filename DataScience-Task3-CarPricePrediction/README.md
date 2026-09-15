# Data Science Task 3: Car Price Prediction with Machine Learning

## Project Overview
This project builds a predictive Linear Regression model using Python to estimate used car selling prices based on attributes like vehicle age, engine power, mileage, fuel type, and transmission.

## Key Workflow & Techniques
- **Feature Engineering:** Calculated present-day vehicle age based on the manufacturing year.
- **Data Cleaning:** Extracted numeric values from string-heavy text columns (`mileage`, `engine`, `max_power`).
- **Categorical Encoding:** Applied one-hot encoding (`pd.get_dummies`) to handle categorical features (`fuel_type`, `seller_type`, `owner`).
- **Modeling & Evaluation:** Evaluated performance on test data using Mean Absolute Error (MAE) and $R^2$ Score alongside actual vs. predicted price visualizations.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## How to Run
1. Clone this repository.
2. Ensure `car data.csv` is placed in the project directory.
3. Open `Car_Price_Prediction.ipynb` in Jupyter Notebook and run all cells.