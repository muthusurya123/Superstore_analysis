# Superstore Sales Data Analysis & Predictive Modeling

## Project Overview
This project focuses on **data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling** using a Superstore Sales dataset.

The goal is to extract meaningful business insights and build a machine learning model to predict future profit values based on sales-related features.

---

## Features

### Data Cleaning
- Handled missing values
- Removed duplicates
- Processed categorical features
- Converted date columns into useful time-based features

### Exploratory Data Analysis (EDA)
- Sales distribution analysis
- Profit analysis
- Category-wise and region-wise sales trends
- Correlation analysis
- Business insights through visualizations

### Data Visualization
Visualizations were created using:
- Matplotlib
- Seaborn

Charts included:
- Sales vs Profit trends
- Category analysis
- Regional performance
- Correlation heatmaps
- Actual vs Predicted plots

---

## Predictive Modeling Using Machine Learning

A supervised machine learning model was built to **predict future profit values**.

### Algorithms Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

After evaluation, **Random Forest Regressor** performed best.

### Model Evaluation Metrics
The model was evaluated using:

- **R² Score**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

### Future Prediction Example
The trained model can predict future profit based on:

- Year
- Month
- Sales
- Quantity
- Discount
- Category
- Sub-category
- Region
- Customer Segment

Example prediction:

```python
Category = Technology
Sub-Category = Phones
Region = West
Year = 2026
Sales = 5000
Discount = 10%
```

The model predicts the expected **future profit** for the given conditions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```text
superstore-sales-project/
│── data/
│   └── superstore_sales.csv
│
│── analysis/
│   └── sales_analysis.ipynb
│
│── README.md
```

---

## Learning Outcomes
This project helped in understanding:

- Data preprocessing
- Data visualization
- Exploratory Data Analysis (EDA)
- Supervised Machine Learning
- Model evaluation techniques
- Predictive analytics