# Appliances Energy Prediction: A Linear Regression Approach

This project explores the factors influencing household energy consumption using a multivariate Linear Regression model. By analyzing data from a smart home environment (including temperature and humidity sensors), the goal is to predict energy use and identify key environmental drivers.

## 📈 Project Overview
Predicting energy consumption is a core challenge for smart-grid integration and product energy efficiency. This analysis follows a rigorous Data Science pipeline:
* **Exploratory Data Analysis (EDA):** Investigating the correlation between indoor/outdoor environmental factors and energy spikes.
* **Feature Engineering:** Selection and transformation of weather-related variables to improve model sensitivity.
* **Regression Modeling:** Implementation of a Linear Regression model to quantify the impact of each sensor reading on total appliance energy usage.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `pandas` & `numpy`: Advanced data wrangling and matrix operations.
    * `seaborn` & `matplotlib`: Heatmaps and residual plots for model validation.
    * `scikit-learn`: Linear regression implementation and performance metrics.

## 🧪 Model Evaluation
The model was evaluated using standard regression metrics to ensure predictive accuracy:
* **Mean Absolute Error (MAE)** & **Root Mean Squared Error (RMSE)**
* **R-squared ($R^2$):** To measure the proportion of variance explained by the environmental features.

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies: `pip install pandas matplotlib seaborn scikit-learn`.
3. Open `DSE_LinearRegression_AppEnergy_Final_MVL2_0.ipynb` in your preferred Jupyter environment.
4. Run the cells to view the data transformation and model coefficients.
