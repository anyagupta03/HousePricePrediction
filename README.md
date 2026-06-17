
# 🏠 House Price Prediction

## 📌 Project Overview

This project builds a regression model to predict house prices based on property features like area, number of rooms, location, and amenities using Python and Machine Learning.

The main objective is to:
- Predict house prices accurately
- Identify which features influence price the most
- Compare performance of two ML models

---

## 🎯 Problem Statement

Real estate buyers and sellers often rely on guesswork to estimate property value. This project automates price estimation using historical data and regression techniques.

---

## 📂 Dataset

Dataset used: **Housing Prices Dataset**

Source: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

- 545 houses with 13 features
- Dataset file: `Housing.csv`

---

## 🛠️ Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## ✅ Tasks Performed

### 1. Data Loading & Exploration
- Loaded dataset using Pandas
- Displayed first 10 rows
- Checked dataset shape (545 rows, 13 columns)
- Identified target column: `price`

### 2. Data Cleaning
- Removed duplicate rows
- Handled missing values
- Applied one-hot encoding on categorical columns (yes/no fields)

### 3. Model Building
- Split data into 80% training and 20% testing
- Trained **Linear Regression** model
- Trained **Random Forest Regressor** model
- Compared both models using MAE, RMSE, and R²

### 4. Data Visualization
- Histogram of house price distribution
- Correlation heatmap of all features
- Actual vs Predicted price scatter plot

### 5. Insights & Summary
- Identified key features influencing price
- Wrote business recommendation based on findings

---

## 📊 Project Results

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | 9,70,043 | 13,24,507 | 0.65 |
| Random Forest | 10,21,546 | 14,00,566 | 0.61 |

✅ **Linear Regression** performed better on this dataset.

---

## 📈 Visualizations

### Chart 1 — Price Distribution
![Price Distribution](charts/chart1_price_distribution.png)

### Chart 2 — Correlation Heatmap
![Correlation Heatmap](charts/chart2_correlation_heatmap.png)

### Chart 3 — Actual vs Predicted
![Actual vs Predicted](charts/chart3_actual_vs_predicted.png)

---

## 🔍 Key Insights

- **Area** is the strongest predictor of house price
- **Bathrooms** and **air conditioning** significantly boost price
- Number of bedrooms had surprisingly less impact than expected
- Properties on main roads and preferred areas command higher prices

---

## 💡 Business Recommendation

Real estate businesses should focus on marketing **total area and bathroom count** over bedroom count. Adding air conditioning and ensuring main road connectivity can significantly increase a property's resale value.

## 📁 Project Structure

HousePricePrediction/

│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── README.md
└── charts/
├── chart1_price_distribution.png
├── chart2_correlation_heatmap.png
└── chart3_actual_vs_predicted.png

---

## ▶️ How to Run

1. Clone the repository
git clone https://github.com/AnyaGupta/HousePricePrediction.git

2. Install required libraries
pip install pandas scikit-learn matplotlib seaborn jupyter

3. Open Jupyter Notebook
jupyter notebook

4. Run `analysis.ipynb`

---

## 👩‍💻 Author

Anya Gupta

---

## 📁 Project Structure
