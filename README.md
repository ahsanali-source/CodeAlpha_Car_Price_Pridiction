# CodeAlpha_Car_Price_Pridiction
An end-to-end Data Science project that predicts used car prices using regression techniques. The workflow covers everything from data loading and feature engineering to model training, evaluation, and visual analysis.

## 📌 Project Overview
The objective of this project is to build a predictive model that estimates the selling price of a used vehicle based on its historical market data and physical characteristics. 

### 🚀 Key Features of the Workflow:
1. **Data Collection & Feature Selection:** Loaded car specifications including brand identity, vehicle age (`Year`), current showroom price (`Present_Price`), mileage (`Driven_kms`) and categorical factors like `Fuel_Type`, `Transmission` and `Owner` types.
2. **Data Preprocessing & Feature Engineering:** 
   * Handled categorical text variables using **One-Hot Encoding** to convert them into machine readable format.
   * Normalized numerical features using **StandardScaler** to ensure all inputs share a uniform scale.
   * Leveraged Scikit-learn **Pipelines** to stream preprocessing and modeling seamlessly without data leakage.
3. **Model Training:** Split the dataset into an 80/20 train-test ratio and trained a **Linear Regression** model to find linear relationships between vehicle attributes and the final selling price.
4. **Evaluation & Visualization:** Evaluated performance metrics (MAE, RMSE and $R^2$ Score) and used **Matplotlib** and **Seaborn** to plot actual vs. predicted prices alongside an error (residuals) distribution graph.

## 🛠️ Tech Stack Used
* **Language:** Python
* **Data Manipulation:** Pandas & NumPy
* **Machine Learning:** Scikit-learn
* **Data Visualization:** Matplotlib & Seaborn
