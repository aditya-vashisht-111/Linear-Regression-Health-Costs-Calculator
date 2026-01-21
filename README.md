# 💻 Linear Regression Health Costs Calculator

This project predicts individual medical/insurance costs using machine learning.  
A Linear Regression model is trained on demographic and lifestyle features such as **age, BMI, smoking status, and dependents** to estimate medical charges.
---

## 🧠 Project Description

The notebook loads and processes the dataset, trains a Linear Regression model, evaluates performance, and allows predictions for new input data. This fulfills the project requirements for the FreeCodeCamp certification.

---

## 📂 Files in This Repository

```
├── Linear_Regression_Health_Costs_Calculator.ipynb
├── README.md
└── (optional) data.csv
```

---

## 📊 Dataset Features

The dataset includes the following columns:

| Feature   | Description |
|---|---|
| age | Age of the person |
| sex | Male/Female |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Whether the person smokes |
| region | Geographic region |
| charges | *(target)* Insurance/medical cost |

---

## 🧪 Model Used

The project uses:

- **Linear Regression (Scikit-learn)**

The model is trained to predict the `charges` column.

---

## 🔍 Workflow Overview

The notebook includes:

✔ Data loading  
✔ Data cleaning  
✔ Categorical encoding  
✔ Train/Test splitting  
✔ Model training  
✔ Evaluation metrics  
✔ Test predictions  

Evaluation uses:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## ▶️ Running the Notebook

1. Clone this repository
2. Install required Python dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```
   jupyter notebook
   ```
4. Run the notebook:
   `Linear_Regression_Health_Costs_Calculator.ipynb`

---

## 🚀 Making Predictions

At the end of the notebook, you can modify the input fields to estimate new medical costs.  
Example simulated input:

```python
model.predict([[age, bmi, children, smoker, region]])
```
