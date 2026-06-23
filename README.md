# House Price Prediction - Linear Regression

## 📊 Project Overview
A machine learning model that predicts house prices based on features like square footage, bedrooms, bathrooms, and age.

## 📈 Model Performance
- **R² Score:** 0.99 (99% accurate!)
- **RMSE:** $12,729.21
- **MAE:** $11,443.27

## 🔧 Features Used
- Square Feet
- Bedrooms
- Bathrooms
- Age of House

## 📝 What I Learned
- Load & explore data with pandas
- Train/test split (80-20)
- Linear Regression with scikit-learn
- Model evaluation metrics (R², RMSE, MAE)
- Visualization (scatter plots, residual plots)

## 🎯 Key Insight
The model explains **99% of price variation** in the data. This means:
- 1 more sq ft → adds ~$83 to price
- 1 more bedroom → adds ~$4,435 to price
- 1 year older → subtracts ~$5,337 from price

## 📂 Files
- `Linear_Regression_pj.ipynb` - Full project code
- `house_data.csv` - Dataset (25 houses)

## 🚀 How to Use
1. Open the notebook
2. Run all cells
3. See predictions on test data
4. Modify house features to get predictions

---
**Built with:** Python, pandas, scikit-learn, matplotlib
