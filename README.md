# snehal_mhetre_CIE2_AD3240
Crop Yield Prediction using Linear Regression to estimate crop production based on agricultural factors.
# 🌾 Crop Yield Prediction Using Linear Regression

## 📌 Project Overview
This project focuses on predicting crop yield using Machine Learning techniques, specifically Simple Linear Regression and Multiple Linear Regression.

The model analyzes agricultural factors such as rainfall, soil quality, farm size, sunlight hours, and fertilizer usage to estimate crop production.

The main objective is to understand how different agricultural parameters influence crop yield and build a regression model that provides data-driven predictions.

## 🎯 Project Objectives
- Predict crop yield using Linear Regression.
- Understand the relationship between agricultural factors and crop production.
- Perform Exploratory Data Analysis (EDA).
- Compare Simple and Multiple Linear Regression models.
- Evaluate model performance using regression metrics.
- Analyze regression assumptions and multicollinearity.

## 📊 Dataset Information
The dataset contains **200 observations** and five independent variables.

| Feature | Description |
|---|---|
| rainfall_mm | Rainfall measurement |
| soil_quality_index | Soil quality indicator |
| farm_size_hectares | Farm area |
| sunlight_hours | Sunlight duration |
| fertilizer_kg | Fertilizer quantity |
| crop_yield | Target variable |

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Google Colab

## ⚙️ Project Implementation

1. **Data Collection:** Load the crop yield dataset.
2. **Data Preprocessing:** Handle missing values using median imputation and remove duplicate records.
3. **Exploratory Data Analysis:** Analyze data using histograms, boxplots, scatter plots, and correlation heatmaps.
4. **Manual Regression:** Implement regression calculations using normal equations.
5. **Data Splitting:** Divide the dataset into 80% training and 20% testing data.
6. **Simple Linear Regression:** Train a model using the feature with the highest absolute correlation with crop yield.
7. **Multiple Linear Regression:** Train a model using all five input features.
8. **Model Evaluation:** Compare the baseline, simple regression, and multiple regression models.
9. **Assumption Checking:** Examine regression assumptions and multicollinearity using VIF.
10. **Prediction:** Estimate crop yield for new input values.

## 📈 Model Evaluation Metrics
The models are evaluated using:

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Coefficient of Determination
- **Adjusted R²:** Adjusted coefficient of determination

## 📉 Visualizations
- Crop Yield Distribution Histogram
- Boxplot for Outlier Detection
- Feature vs Crop Yield Scatter Plots
- Correlation Heatmap
- Regression Line Visualization
- Actual vs Predicted Plot
- Residual Plot
- Residual Distribution Histogram

## 🔍 Advanced Analysis
- Standardized Regression Coefficients
- Multicollinearity Detection using Variance Inflation Factor (VIF)
- Regression Assumption Checking
- Baseline vs Simple vs Multiple Regression Comparison

## 🚀 Future Enhancements
- Integrate real-time weather information.
- Include additional agricultural features.
- Experiment with Polynomial Regression and Decision Tree Regression.
- Develop an interactive crop yield prediction web application.

## 📝 Conclusion
This project demonstrates the application of Data Science and Machine Learning in agriculture. By implementing Simple and Multiple Linear Regression, it explores how rainfall, soil quality, farm size, sunlight, and fertilizer usage influence crop yield.

It provides practical experience in data preprocessing, exploratory data analysis, regression modeling, model evaluation, and statistical analysis.

---

⭐  https://github.com/complexiota.
