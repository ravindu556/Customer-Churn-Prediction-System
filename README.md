# Customer Churn Prediction System

This project focuses on predicting customer churn using machine learning techniques. It includes data preprocessing, exploratory data analysis (EDA), class balancing, and model evaluation using Decision Tree and Neural Networks.

---

## 📊 Dataset
- Telco Customer Churn Dataset
- Contains customer demographics, services, and billing information
- Target variable: **Churn (Yes/No)**

---

## ⚙️ Features of the Project

### 🔍 Exploratory Data Analysis (EDA)
- Checked missing values and duplicates
- Visualized churn distribution
- Analyzed tenure, monthly charges, and contract types
- Correlation heatmap

---

### 🧹 Data Preprocessing
- Converted data types (TotalCharges)
- Handled missing values
- One-hot encoding for categorical variables
- Train-test split
- Feature scaling using StandardScaler

---

### ⚖️ Handling Class Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)**
- Balanced dataset from:
  - Before: 73% / 27%
  - After: 50% / 50%

---

### 🤖 Models Implemented

#### 1. Decision Tree Classifier
- Hyperparameter tuning using GridSearchCV
- Evaluated using accuracy, precision, recall, F1-score
- Feature importance analysis

#### 2. Neural Network (Deep Learning)
- Built using TensorFlow/Keras
- Tuned neurons and dropout
- Compared multiple configurations
- Final tuned model selected based on F1-score

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------|----------|--------|---------|
| Decision Tree | 0.74 | 0.50 | 0.70 | 0.59 |
| Neural Network | 0.78 | 0.57 | 0.61 | 0.59 |

### ROC-AUC:
- Decision Tree: **0.8031**
- Neural Network: **0.8283**

👉 Neural Network performed better overall.

---

## 📊 Visualizations
- Confusion Matrix
- ROC Curve
- Feature Importance
- Data Distribution Plots

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- SMOTE (Imbalanced-learn)

---

## 🚀 Key Learnings
- Handling imbalanced datasets
- Model comparison and evaluation
- Hyperparameter tuning
- Building neural networks
- Data preprocessing pipeline

---

## 📌 Future Improvements
- Try advanced models (XGBoost, Random Forest)
- Deploy as web application
- Improve feature engineering

---

## 👨‍💻 Author
Ravindu Edirisingha
