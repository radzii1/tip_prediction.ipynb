# tip_prediction.ipynb
# 💰 Tip Prediction with Linear Regression

This project uses the **Seaborn Tips Dataset** to build a machine learning model that predicts the amount of tip based on features like total bill, gender, smoking status, time of day, and party size.

---

## 📊 Dataset Overview

The dataset includes:

- `total_bill`: Total bill (in USD)
- `tip`: Tip given (target variable)
- `sex`: Gender of the customer
- `smoker`: Whether the customer is a smoker
- `day`: Day of the week
- `time`: Lunch or Dinner
- `size`: Number of people in the group

---

## 🔧 Workflow

1. **Data Cleaning & EDA**: Used Pandas & Seaborn to explore distributions and correlations  
2. **Preprocessing**: Converted categorical features using one-hot encoding  
3. **Modeling**: Trained a Linear Regression model using `scikit-learn`  
4. **Evaluation**: Measured performance using R² Score and Mean Squared Error  
5. **Interpretation**: Analyzed feature coefficients to understand what influences tip amount

---

## 📈 Model Results

- **R² Score**: 0.76 (example — update with your score)
- **Top Features**: `total_bill`, `size`, `smoker_Yes`

---

## 🧠 Key Learnings

- Basics of regression modeling
- How to handle categorical data for ML
- Evaluating and interpreting ML model results

---

## 📦 Requirements

```bash
pip install pandas seaborn matplotlib scikit-learn
