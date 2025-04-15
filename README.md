# 🚗 CO2 Emission Prediction using Linear & Polynomial Regression

This project aims to predict the CO2 emissions of vehicles based on their fuel consumption and engine specifications using both **Linear Regression** and **Polynomial Regression** models.

## 📊 Dataset

The dataset includes information on various vehicles, focusing on fuel consumption and CO2 emissions.

### Features Used:
- `Engine_Size`: Engine displacement (L)
- `Cylinders`: Number of engine cylinders
- `Fuel_Consumption_City`: Fuel consumption in city driving (L/100km)
- `Fuel_Consumption_Hwy`: Fuel consumption on highways (L/100km)
- `Fuel_Consumption_Comb`: Combined fuel consumption (L/100km)
- `Fuel_Consumption_Comb(mpg)`: Combined fuel consumption in MPG
- `CO2_Emissions`: CO2 emissions (g/km)

## 🔍 Project Workflow

- Data loading and preprocessing
- Exploratory Data Analysis (EDA) and visualizations
- Polynomial degree tuning with RMSE tracking
- Comparison between Linear and Polynomial regression models

## 📈 Model Performance

| Model                | R²    | MAE   | RMSE  |
|---------------------|-------|-------|-------|
| Linear Regression   | 0.87  | 12.01 | 15.32 |
| Polynomial (degree=3) | 0.93  | 9.45  | 11.28 |

## 🛠 Libraries Used

- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `scikit-learn`

## 📷 Sample Visualizations

- Distribution of CO2 Emissions
- Correlation heatmap
- Scatter plots of fuel consumption vs emissions
- Polynomial degree vs RMSE plot


## 🚀 Future Improvements

- Implement regularization techniques (Ridge, Lasso)
- Try alternative regression models (e.g., Random Forest, XGBoost)
- Evaluate model performance across different vehicle types or years

## 📁 Project Structure

