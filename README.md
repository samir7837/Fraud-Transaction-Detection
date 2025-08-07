# 🕵️‍♂️ Fraud Transaction Detection Using Machine Learning

An end-to-end project focused on detecting fraudulent financial transactions using machine learning. The notebook covers feature engineering based on customer and terminal behavior, implements multiple classification models, and evaluates their performance using precision, recall, F1-score, and ROC-AUC metrics.

---

## 📌 Objectives

- Detect fraudulent transactions from a simulated real-time dataset.
- Create time-based features using rolling windows per terminal and customer.
- Compare and evaluate multiple machine learning models for performance.

---

## 📦 Dataset

The dataset simulates real-world financial transactions with millions of records and includes features such as:

- `TX_ID`, `TX_DATETIME`, `CUSTOMER_ID`, `TERMINAL_ID`, `TX_AMOUNT`, and `TX_FRAUD`.

📥 **Download Dataset**:  
[Click here to download the dataset (Google Drive)](https://drive.google.com/file/d/1RmyroE7zHcB6-BrJ-wEnXR1rP_W86WaJ/view?usp=sharing)

> After downloading, extract the file and place the contents inside the `data/` directory before running the notebook.


---

## 🛠️ Technologies & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🧠 Models Used

| Model               | Purpose                                 |
|--------------------|------------------------------------------|
| Logistic Regression| Baseline comparison model                |
| Random Forest       | Strong performer on structured data      |
| XGBoost             | Gradient boosting with high accuracy     |
| Stacking Classifier | Combines strengths of multiple models    |

---

## 📈 Results Summary

- **Accuracy**: `99.77%`
- **ROC-AUC Score**: `0.9989`
- **Fraud Recall**: ~`99.7%` — model successfully catches almost all fraud cases
- Some false positives exist, which can be improved with threshold tuning.

---
 
## 📌 Key Highlights

1. Engineered rolling-window fraud and spend behavior features.

2. Balanced class performance using ensemble learning (stacking).

3. High recall ensures minimal frauds go undetected.

4. Fully documented, readable, and scalable notebook code.

---

## 📜 License
This project is open-source and available under the MIT License.

---

⭐ Found this helpful? Leave a star and consider contributing!

---
