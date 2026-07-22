# 🏦 Bank Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

The **Bank Loan Approval Prediction** project uses Machine Learning to predict whether a loan application should be **Approved** or **Rejected** based on an applicant's personal and financial information.

The project automates the loan approval prediction process by analyzing historical loan application data. It helps financial institutions make faster, more consistent, and data-driven decisions.

---

## 🎯 Project Objective

- Predict whether a loan application will be approved or rejected.
- Reduce manual effort in loan approval.
- Improve decision-making using Machine Learning.
- Analyze historical applicant data to identify important factors affecting loan approval.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset Information

**Dataset:** Loan Prediction Dataset

### Training Dataset
- Records: **614**
- Features: **13**

### Target Variable

| Value | Meaning |
|-------|---------|
| Y | Loan Approved |
| N | Loan Rejected |

### Input Features

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

---

## ⚙️ Project Workflow

```
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Missing Value Handling
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Encoding
        │
        ▼
Train-Test Split
        │
        ▼
Logistic Regression Model
        │
        ▼
Model Evaluation
        │
        ▼
Loan Approval Prediction
```

---

## 📊 Exploratory Data Analysis

The following analysis was performed:

- Loan Status Distribution
- Credit History vs Loan Status
- Missing Value Analysis

### Key Observation

Applicants with a **good Credit History** have a significantly higher chance of loan approval.

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Logistic Regression

### Why Logistic Regression?

- Suitable for binary classification.
- Fast and efficient.
- Easy to interpret.
- Performs well on structured tabular data.

---

## 📈 Model Performance

### Accuracy

**84.55%**

### Evaluation Metrics

- Accuracy Score
- Confusion Matrix

The model correctly predicts loan approval for most applicants and provides reliable classification performance.

---

## 📸 Project Outputs

The repository includes the following outputs:

- Dataset Preview
- Missing Values Analysis
- Loan Status Distribution Graph
- Credit History Analysis Graph
- Model Accuracy
- Confusion Matrix
- Final Loan Prediction Output

---

## 💻 How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/your-username/Bank-Loan-Approval-Prediction.git
```

2. Open the project in **Google Colab** or **Jupyter Notebook**.

3. Install the required libraries (if needed).

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run all notebook cells in sequence.

5. Enter applicant details in the final prediction section.

6. The model will predict:

- ✅ Loan Approved
- ❌ Loan Rejected

---

## 📁 Project Structure

```
Bank-Loan-Approval-Prediction/
│
├── Loan_Prediction.ipynb
├── train.csv
├── test.csv
├── README.md
├── accuracy.png
├── confusion_matrix.png
├── loan_status_distribution.png
├── credit_history_analysis.png
└── prediction_output.png
```

---

## 🚀 Future Improvements

- Use Random Forest
- Use XGBoost
- Hyperparameter Tuning
- Build a Flask or Streamlit Web Application
- Deploy on Cloud Platforms

---

## 👩‍💻 Author

**Sneha Verma**

B.Tech – Computer Science & Engineering (Artificial Intelligence)

Noida Institute of Engineering and Technology (NIET)

---

## ⭐ Project Summary

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction using Logistic Regression. The model achieved an accuracy of **84.55%**, making it suitable as a beginner-friendly AI/ML project for learning and portfolio purposes.
