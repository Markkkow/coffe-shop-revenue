# ☕ Coffee Shop Revenue Intelligence & Demand Forecasting

> End-to-end business analytics on **real 2024–2025 POS transaction data** from a coffee shop — covering revenue trends, product performance, demand patterns, and 90-day revenue forecasting using Facebook Prophet + Random Forest.

---

## 📌 What Makes This Project Unique

Most public coffee datasets are either synthetic or over 5 years old. This project uses **actual Point-of-Sale (POS) transaction data from March 2024 to March 2025**, making the insights genuinely relevant to today's consumer behavior.

The analysis goes beyond basic EDA by combining:
- **Granular time decomposition** (hourly, daily, weekly, monthly)
- **Dual forecasting models**: Prophet for long-term trends + Random Forest for short-term precision
- **Actionable business recommendations** tied directly to data

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| 📅 Data Period | Mar 2024 – Mar 2025 |
| 🧾 Total Transactions | 3,547 |
| 💰 Total Revenue | $112,245+ |
| ☕ Top Product | Americano with Milk |
| ⏰ Peak Hours | Morning & Afternoon |
| 🏆 Best Day | Tuesday |
| 🔮 Forecast Horizon | 90 days |

---

## 🗂️ Project Structure

```
coffee-shop-analysis/
│
├── data/
│   └── coffee_sales.csv               # Real POS transaction data (2024–2025)
│
├── notebooks/
│   └── coffee_shop_analysis.ipynb     # Full analysis notebook
│
├── images/
│   ├── monthly_trend.png
│   ├── hourly_pattern.png
│   ├── day_of_week.png
│   ├── product_analysis.png
│   ├── heatmap_tod_product.png
│   ├── heatmap_day_hour.png
│   ├── daily_revenue_trend.png
│   ├── revenue_forecast.png
│   ├── prophet_components.png
│   └── rf_prediction.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/username/coffee-shop-analysis.git
cd coffee-shop-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook notebooks/coffee_shop_analysis.ipynb
```

Go to **Kernel → Restart & Run All**

---

## 📦 Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
prophet>=1.1.0
jupyter>=1.0.0
```

---

## 📈 Analysis Highlights

### ⏰ Demand Forecasting (Prophet)
Used Facebook Prophet to forecast daily revenue for the next 90 days, capturing weekly and yearly seasonality patterns from 12+ months of historical data.

### 🤖 Revenue Prediction (Random Forest)
Built a lag-feature-based Random Forest model using previous day/week revenue as predictors — enabling short-term daily revenue estimation.

### 🔥 Revenue Heatmap
Mapped revenue by Day of Week × Hour of Day to pinpoint the exact windows of peak customer activity — directly actionable for staffing decisions.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.3-lightblue?logo=pandas)
![Prophet](https://img.shields.io/badge/Prophet-1.1-red)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 👤 Author

**[Your Name]**
📧 email@example.com
🔗 [LinkedIn](https://linkedin.com/in/username) | [GitHub](https://github.com/username)

---

## 📄 License

This project is licensed under the MIT License.
