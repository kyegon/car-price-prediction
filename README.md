# Car Price Prediction Analysis

A comprehensive machine learning project analyzing used car prices and building predictive models using various regression techniques.

## Project Overview

This project demonstrates a complete data science workflow for predicting used car prices using the CarDekho dataset. The analysis includes exploratory data analysis, feature engineering, multiple regression models, and comprehensive evaluation.

##  Project Structure

car-price-prediction/
│
├── data/
│   ├── raw/                    # Original dataset (cardekho.csv)
│   └── processed/              # Cleaned and engineered data
│
├── notebooks/
│   └── Car_Price_Analysis.ipynb    # Main analysis notebook
│
├── scripts/                    # Utility scripts
│
├── models/                     # Saved trained models
│
├── results/                    # Visualizations and analysis results
│
├── docs/                       # Additional documentation
│
├── requirements.txt            # Python dependencies
│
└── README.md                   # Project documentation


## Key Analysis Steps

1. **Data Cleaning & Preprocessing** - Handling missing values, outliers, and data validation
2. **Exploratory Data Analysis** - Understanding distributions, correlations, and patterns
3. **Feature Engineering** - Creating new features like car age, price per km, etc.
4. **Model Training** - Linear, Ridge, Lasso, and Polynomial Regression
5. **Model Evaluation** - Comprehensive comparison using R², RMSE, MAE metrics
6. **Visualization** - Interactive plots and charts for insights

## Installation & Usage

```bash
# Clone repository
git clone https://github.com/YourUsername/car-price-prediction.git
cd car-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook notebooks/Car_Price_Analysis.ipynb
```

## Requirements
See requirements.txt for complete package dependencies.

## Dataset
The analysis uses the Car Details from CarDekho dataset (https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho), containing features like:

- selling_price : Target variable
- carAge : Age of the car
- km_driven : Kilometers driven
- engine : Engine size (CC)
- max_power : Maximum power (bhp)
- fuel_type : Fuel type (Petrol/Diesel/CNG)
- transmission : Transmission type (Manual/Automatic)
  
## Author
@kyegon

## License
This project is licensed under the MIT License.
