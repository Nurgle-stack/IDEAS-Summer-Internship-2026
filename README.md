# IDEAS-Summer-Internship-2026
# Retail Sales Data Analysis
**IDEAS Summer Internship 2026 — ISI Kolkata**

---

## Project Overview
This project performs an end-to-end analysis of a retail sales dataset as part of the IDEAS Summer Internship Program 2026. It covers time-series revenue analysis, customer behaviour profiling, product category performance, and unsupervised machine learning using K-Means clustering on the MNIST digits dataset.

---

## Dataset
- **File:** `retail_sales_dataset.csv`
- **Records:** 2,000 transactions
- **Columns:** Transaction ID, Date, Customer ID, Product Category, Quantity, Price per Unit, Total Amount
- **Source:** Provided via Google Drive by IDEAS, ISI Kolkata

---

## Notebook Structure
The analysis is contained in a single Jupyter Notebook:

`08_Retail_Sales_Data_Analysis_Summer_2026.ipynb`

| Question | Description |
|----------|-------------|
| Q1 | Import libraries and load dataset |
| Q2 | Convert Date column to datetime and verify data types |
| Q3 | Inspect dataset shape and check for null values |
| Q4 | Compute monthly revenue |
| Q5 | Compute weekly revenue |
| Q6 | Identify best-selling product category |
| Q7 | Top 5 customers by total spending |
| Q8 | Top 5 customers by average order value |
| Q9 | Cumulative revenue over time |
| Q10 | Pivot table — Category × Month revenue |
| Q11 | Load MNIST digits dataset |
| Q12 | Apply K-Means clustering (k=10) |
| Q13 | Evaluate clustering using macro-averaged F1 score |

---

## Key Results
- **Peak month:** May 2023 — ₹1,01,279
- **Best-selling category:** Clothing — ₹3,12,997
- **Top customer:** CUST281 — ₹3,438.50 total spend
- **Cumulative revenue:** ₹8,97,742 by January 2024
- **K-Means F1 Score (MNIST):** 0.8628

---

## Technologies Used
- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Author
**H. Siamthianlam**
Assam Don Bosco University
B.Tech in Computer Science and Engineering | Batch 2024-2028

---

*Submitted to IDEAS – Institute of Data Engineering, Analytics and Science Foundation, ISI Kolkata*
*Internship Period: 18th May 2026 – 14th June 2026*
