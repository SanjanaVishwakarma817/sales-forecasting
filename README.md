# Sales Forecasting Model

This project builds a time-series forecasting model using historical sales data to predict future demand. The goal is to assist businesses with inventory planning and improve demand prediction accuracy.

## 📂 Dataset
- The dataset includes date, sales, and other related features.
- Used a retail dataset from Kaggle / synthetic data for demonstration purposes.

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn (Linear Regression, Random Forest)
- Matplotlib for visualization

## ✅ Key Features
- Time-based features: month, day of week, weekend indicator
- Lag feature: previous day’s sales
- Rolling average to capture trends
- Comparison with baseline prediction using lag values

## 📈 Results
- Random Forest model achieved a **15% improvement** over baseline.
- Visualized actual vs predicted sales to showcase model accuracy.

## 📂 Project Structure
sales-forecasting/
├── sales_forecasting.ipynb
├── data/
│ └── sales_data.csv
├── README.md
└── requirements.txt
