#  Sales & Demand Forecasting

A Machine Learning project that forecasts future business sales using
historical data and time-series analysis.

---

##  Project Overview

This project analyzes the **Sample Superstore dataset** to uncover sales
trends and forecast future revenue using a Linear Regression model.
The goal is to help businesses make data-driven decisions by predicting
upcoming sales performance.

---

##  Dataset

- **Name:** Sample - Superstore
- **Source:** Tableau Sample Dataset (widely used for business analytics practice)
- **Key Columns Used:** `Order Date`, `Sales`, `Profit`, `Category`

---

##  Technologies & Libraries Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Business-friendly charts |
| Scikit-learn | ML model training & evaluation |
| Jupyter Notebook | Development environment |

---

##  Project Workflow

1. **Data Loading** — Load the Superstore CSV with correct encoding
2. **Data Cleaning** — Check for null values, convert dates, sort chronologically
3. **Feature Engineering** — Extract Year, Month, and Year-Month period columns
4. **Monthly Aggregation** — Group sales by month for time-series analysis
5. **Visualization** — Plot historical monthly sales trend
6. **Model Training** — Train a Linear Regression model on a time index
7. **Model Evaluation** — Measure accuracy using Mean Absolute Error (MAE)
8. **Forecasting** — Predict sales for the next 12 months
9. **Forecast Visualization** — Plot historical vs predicted sales on one chart

---

##  Results

- The model successfully identifies the **overall sales trend** across 4 years of data
- Generates a **12-month future forecast** with a business-ready visualization
- Model performance is measured using **MAE (Mean Absolute Error)**

---

##  Repository Structure
```
FUTURE_ML_01/
│
├── Sales_Demand_Forecasting.ipynb   # Main Jupyter Notebook
├── Sample - Superstore.csv          # Dataset
├── .gitignore                       # Git ignore file
└── README.md                        # Project documentation
```

---

##  How to Run

1. Clone this repository:
```bash
   git clone https://github.com/akumalla2711-a11y/FUTURE_ML_01.git
```

2. Install required libraries:
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook:
```bash
   jupyter notebook Sales_Demand_Forecasting.ipynb
```

4. Run all cells from top to bottom.

---

##  Skills Demonstrated

- Time-series data analysis
- Business data visualization
- Feature engineering on date columns
- Machine Learning model training & evaluation
- Sales forecasting & business interpretation

---

## 👤 Author
A ANANTH ADITYA
https://github.com/akumalla2711-a11y
