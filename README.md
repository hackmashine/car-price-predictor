# 🚗 Car price prediction with CatBoost

This project tries to predict the price of a car (sellingprice) based on its characteristics.  
The data is taken from the dataset **vehicle-sales-data** (Kaggle).

---

## 📦 What is used
- Python
- pandas
- scikit-learn
- catboost
- matplotlib

---

## ⚙️ How to launch

1. Install the libraries:
``bash
   pip install catboost pandas scikit-learn matplotlib
2.Download the dataset from Kaggle:
/kaggle/input/vehicle-sales-data/car_prices.csv
3.Run the laptop or script with the code.
Everything is already set up in the code: data loading, training, and model validation.

📊 Results

The model is trained with the best parameters (selected in advance).

The error on the test (MAE) is approximately ~$886.

The most important feature is the MMR (the market price according to the auction estimate).

The importance of signs

The code plots the importance of the features:

mmr is the most important (≈70%)

then there are model, odometer, make, etc.

What can be improved

try other models (LightGBM, XGBoost),

add more features (for example, regional prices),

make a web application for price prediction.
