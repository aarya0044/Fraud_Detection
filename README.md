# Financial Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on building a machine learning model to proactively detect fraudulent financial transactions.  
The objective is to identify high-risk transactions while minimizing false positives, using a real-world large-scale dataset.


---

## 📂 Dataset Information
- Dataset contains **~6.3 million financial transactions**
- Each record represents a single transaction with balance, amount, and transaction type details
- Target variable: `isFraud` (1 = Fraud, 0 = Not Fraud)

⚠️ Due to dataset size constraints, the dataset is **not included** in this repository.

---

## 🧪 Methodology
The project follows a structured machine learning workflow:

1. Data loading and understanding  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering and selection  
5. Model building and training  
6. Model evaluation  
7. Business insights and fraud prevention strategies  

---

## 🤖 Models Used
- **Logistic Regression** (Baseline model)
- **Random Forest Classifier** (Primary model)

Random Forest was chosen due to its ability to:
- Handle non-linear relationships
- Manage class imbalance
- Provide feature importance insights

---

## 📊 Model Evaluation
Model performance was evaluated using:
- Precision
- Recall (prioritized due to fraud risk)
- F1-score
- ROC-AUC score
- ROC Curve visualization

---

## 🔍 Key Fraud Indicators Identified
- High transaction amounts
- CASH_OUT and TRANSFER transaction types
- Abnormal balance changes between sender and receiver
- Time-based transaction patterns

---

## 🛡️ Business Recommendations
- Implement real-time fraud monitoring systems
- Introduce stricter verification for high-risk transactions
- Apply transaction amount thresholds
- Enable two-factor authentication for suspicious activities

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 📁 Repository Contents
- `Fraud_Detection_Accredian.ipynb` – Complete analysis and model implementation
- `README.md` – Project overview and methodology
