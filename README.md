# 🧠 Customer Churn Prediction

## 📌 Objective

This project aims to build a machine learning model to **predict customer churn** for a subscription-based business. Using historical customer data — such as demographics, account details, and engagement — the model identifies users at high risk of leaving. This helps businesses **proactively engage and retain** such customers by offering personalized services or retention strategies.

---

## 📊 Dataset

The dataset contains information on:
- **CreditScore**: Customer's credit score
- **Geography**: Customer location
- **Gender**: Male/Female
- **Age**: Customer age
- **Tenure**: Years with the company
- **Balance**: Account balance
- **NumOfProducts**: Products used
- **HasCrCard**: Credit card ownership
- **IsActiveMember**: Account activity status
- **EstimatedSalary**: Estimated annual salary
- **Exited**: Target variable (1 = Churned, 0 = Retained)

---

## 🛠️ Features

- 📊 **EDA & Visualizations**: Churn rate distribution, feature correlation, boxplots, and countplots.
- 🧹 **Preprocessing**: Handling missing values, encoding, scaling.
- 🔍 **Feature Engineering**: Deriving new features like age group, product engagement level.
- 🤖 **Model Training & Comparison**:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Multilayer Perceptron (Neural Network)
- 📈 **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
- 📌 **Feature Importance Analysis**: Identifying key factors influencing churn.

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

### 2. Install Dependencies
```bash
pip install -r requirements.txt

### 3. Launch Jupyter Notebook
```bash
jupyter notebook notebooks/churn_eda_modeling.ipynb


## customer-churn-prediction/
  
  ├── data/                 # Raw dataset
  ├── notebooks/            # Jupyter Notebook with EDA + Modeling
  ├── src/                  # Preprocessing, modeling, visualization scripts
  ├── outputs/              # Saved visualizations and model results
  ├── README.md             # Project overview
  ├── requirements.txt      # Python dependencies
  └── .gitignore

## ✅ Evaluation Criteria

    Functionality: End-to-end churn prediction with comparative analysis.
    
    Code Quality: Modular, reusable, and well-documented.
    
    Visualization: Clear and impactful plots.
    
    Documentation: Thorough project explanation and usage steps.

## 📌 Results Summary

Model	Accuracy	      ROC    AUC
Random Forest	        0.86	 0.91
XGBoost	              0.87	 0.92
Logistic Regression	  0.80	 0.83
SVM	                  0.79	 0.81
KNN	                  0.76	 0.79
Neural Network	      0.84	 0.89

## 📧 Contact

  Prasanna Venkatesh
  prasannavenkatesh.5261@gmail.com
