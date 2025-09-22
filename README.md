# 💳 Credit Card Fraud Analysis (Python + SQL)

## 📌 Overview
This project analyzes **credit card transactions** using **Python (Pandas, Matplotlib, Seaborn)** and **SQLite**.  
The goal is to uncover fraud patterns, transaction distributions, and provide actionable business insights.

---

## 🔍 Key Insights
- **Total transactions:** ~285,000  
- **Fraud cases:** ~492 (0.17%) → indicates **high class imbalance**  
- **Average fraud transaction amount** is higher than normal transactions  
- Transaction amounts are **highly skewed**, so log scale analysis is used  
- Correlation heatmap shows relationships between numeric features  
- Fraud detection requires **anomaly-based techniques** and careful preprocessing

---

## 🛠 Tools Used
- **Python:** Pandas, Matplotlib, Seaborn  
- **SQL:** SQLite queries for data handling  
- **Dataset:** [Credit Card Fraud Dataset (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## 🗂 Dataset
Due to large dataset size, please **download the dataset from Kaggle** and place it in the `data/` folder:


Your Python notebook will read the dataset from this path.

---

## 📸 Visuals

### Fraud vs Non-Fraud Pie Chart
<img width="481" height="504" alt="image" src="https://github.com/user-attachments/assets/98e27a60-680a-4ee1-b5b2-4da834da04f6" />

### Average Transaction Amount Comparison
![Average Transaction Amount](images/avg_amount_comparison.png)

### Transaction Amount Distribution (Log Scale)
![Transaction Amount Distribution](images/transaction_amount_distribution.png)

### Feature Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📝 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/CreditCard-Fraud-Analysis.git
