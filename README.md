# Machine Learning Projects

This repository showcases two machine learning mini-projects built using **Multiple Linear Regression**, demonstrating applied skills in **data preprocessing**, **feature engineering**, and **model evaluation**. These projects simulate real-world use cases in the insurance and real estate industries.

1. **Predicting Health Insurance Costs**
2. **Predicting House Prices**

Each project emphasizes structured problem-solving, business relevance, and end-to-end data workflows.

---

## 📌 1. Predicting Health Insurance Costs

### 📂 File: `ML_Health_Insurance.ipynb`

### 🧠 Objective:
To build a regression model that predicts health insurance charges based on personal and lifestyle factors. This simulation reflects real-world pricing algorithms used by insurers to assess client risk and calculate premiums.

### 📊 Dataset:
- A synthetic dataset containing:
  - `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

### ⚙️ Workflow:
- Performed **Exploratory Data Analysis (EDA)** to understand distributions and correlations
- Converted categorical variables to numeric using **One-Hot Encoding**
- Trained a **Multiple Linear Regression** model using `scikit-learn`
- Evaluated performance using **R-squared (R²)** and **Root Mean Squared Error (RMSE)**

### 📈 Key Insight:
- **Smoking status** and **BMI** emerged as the strongest predictors of high charges
- Demonstrated how even basic linear models can yield meaningful insights for insurance pricing strategies

### ✅ Focused Value:
- Simulates data-driven risk assessment for insurance firms
- Shows ability to clean messy real-world datasets and build explainable models
- Demonstrates stakeholder-friendly insights and metric-driven evaluation

---

## 📌 2. Predicting House Prices

### 📂 File: `ML_House_Pricing.ipynb`

### 🧠 Objectives:
- Identify which housing features most impact pricing (e.g., area, rooms, bathrooms)
- Build a regression model to estimate house prices based on these features
- Understand how well these variables explain price variance

### 📊 Dataset:
- Contains numeric housing attributes:
  - `Area`, `Rooms`, `Bathroom`, `Price`

### ⚙️ Workflow:
- Visualized distributions and feature correlations using **Seaborn**
- Converted categorical variables (if any) and scaled inputs where necessary
- Built and validated a **Multiple Linear Regression** model
- Interpreted model coefficients to explain real-world pricing patterns

### 📈 Key Insight:
- The model found a strong positive relationship between **area**, **number of rooms**, and **price**
- Coefficients reveal which features are most influential in property valuation

### ✅ Focused Value:
- Mimics how real estate firms and banks estimate property values
- Demonstrates hands-on experience with **feature importance**, **regression math**, and **interpretability**
- Applies ML to real business problems with financial outcomes

---

## 🛠️ Tools & Libraries Used:
- **Python** – core programming language
- **Pandas** – data manipulation
- **NumPy** – numerical computing
- **Scikit-learn** – machine learning
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook** – documentation and reproducibility

---
