# 🧪 BRFSS Health Data Analysis & Regression with Python

This project explores health-related data from the **Behavioral Risk Factor Surveillance System (BRFSS)** using Python. The analysis focuses on identifying patterns in **weight change** over time based on demographics such as age, sex, and prior weight. Additionally, the project applies a **simple linear regression model** to estimate housing prices from square footage, showcasing predictive modeling using `scikit-learn`.

---

## 📌 Objectives

- Explore weight change patterns in public health data
- Analyze correlations between current/past weight, height, and age
- Visualize relationships through scatter plots
- Apply a simple linear regression model to real-world housing data
- Demonstrate basic statistical reasoning and prediction

---

## 🧰 Tools & Libraries Used

- `pandas` – Data manipulation and exploration
- `matplotlib` – Visualizations (scatter plots)
- `scikit-learn` – Linear regression modeling
- `Jupyter Notebook` – Code organization and presentation

---

## 📊 Key Analyses

### ✅ BRFSS Health Data
- Summary statistics (mean, median, std deviation)
- Scatter plots:
  - Weight change vs current weight
  - Weight change vs weight a year ago
  - Weight change vs age
- Correlation coefficients for each comparison
- Finding: **Previous weight has the strongest correlation with weight change**

### ✅ Linear Regression (Bonus Task)
- Used a housing dataset to model house prices based on size
- Built a regression line using `LinearRegression` from scikit-learn
- Prediction: A 2,500 sqft house is estimated at **$326,000**

---

## 📂 Files Included

- `brfss-health-analysis-python.ipynb` – Main analysis notebook
- `README.md` – Project documentation

---

## 📷 Sample Visuals

![Summary statistics analysis](https://github.com/user-attachments/assets/1d93d399-d69c-418f-acd8-cfa3c3cd25f6)

![Scatter: Weight Change vs Age](https://github.com/user-attachments/assets/f2d0bc8e-467c-426f-8d27-c90818fbb2b8)

![Weight Change vs Weight a Year Ago](https://github.com/user-attachments/assets/0c66830a-caf0-4310-b319-365e8c959f7f)

![Weight Change vs Current Weight](https://github.com/user-attachments/assets/5a33bc43-f6f7-411e-b415-0db84eb831ae)
---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/brfss-health-analysis-python.git
