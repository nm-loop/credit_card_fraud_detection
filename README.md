# 💳 Credit Card Fraud Detection using Logistic Regression

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using a **Logistic Regression** machine learning model. The workflow includes data loading, exploratory data analysis (EDA), preprocessing, feature scaling, model training, and performance evaluation. The objective is to accurately classify transactions as **genuine** or **fraudulent** while addressing the challenges of an imbalanced dataset.

---

## 🎯 Objectives

- Analyze the credit card transaction dataset.
- Perform Exploratory Data Analysis (EDA).
- Preprocess and standardize the data.
- Train a Logistic Regression model.
- Evaluate the model using multiple performance metrics.
- Identify fraudulent transactions effectively.

---

## 📂 Dataset

The dataset contains anonymized credit card transaction records with the following features:

- **Time** – Time elapsed between transactions.
- **V1 – V28** – PCA-transformed numerical features.
- **Amount** – Transaction amount.
- **Class** – Target variable:
  - **0** → Genuine Transaction
  - **1** → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### Phase 1: Data Loading & Understanding
- Import required libraries
- Load the dataset
- Explore dataset structure
- Check data types and dimensions

### Phase 2: Exploratory Data Analysis (EDA)
- Missing value analysis
- Duplicate record analysis
- Statistical summary
- Class distribution analysis
- Transaction amount distribution
- Transaction time distribution
- Correlation analysis and heatmap

### Phase 3: Data Preprocessing
- Standardize **Time** and **Amount** features
- Remove original columns
- Feature and target separation
- Train-test split using stratified sampling

### Phase 4: Model Building
- Build Logistic Regression model
- Train the model
- Generate predictions
- Predict fraud probabilities

### Phase 5: Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score
- ROC Curve

### Phase 6: Conclusion
- Performance analysis
- Key findings
- Future improvements

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

These metrics provide a comprehensive assessment of the model's effectiveness, especially for an imbalanced fraud detection dataset.

---

## 🚀 Future Improvements

- Apply SMOTE to address class imbalance.
- Train advanced models such as Random Forest, XGBoost, and LightGBM.
- Perform hyperparameter tuning.
- Develop ensemble learning models.
- Deploy the model using Flask, FastAPI, or Streamlit.
- Implement real-time fraud detection systems.

---

## 📁 Repository Structure

```
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── creditcard.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/nm-loop/credit_card_fraud_detection
.git
```

2. Navigate to the project folder.

```bash
cd Credit-Card-Fraud-Detection
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all cells sequentially to reproduce the results.

---

## 📌 Key Highlights

- End-to-end Machine Learning workflow
- Clean and structured Exploratory Data Analysis
- Data preprocessing with feature scaling
- Binary classification using Logistic Regression
- Comprehensive performance evaluation
- Well-documented Jupyter Notebook

---

## 👨‍💻 Author

**Niraj Kumar Maurya**

B.Tech – Computer Science & Engineering  
Data Science & AI Enthusiast

---

## ⭐ Acknowledgements

This project was completed as part of a **Data Science Internship** to demonstrate practical implementation of machine learning techniques for financial fraud detection using Python and Scikit-learn.
