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

### Fraud vs Non-Fraud Bar Plot
<img width="578" height="450" alt="image" src="https://github.com/user-attachments/assets/ac239df3-2dac-4270-a71c-b15275036d2c" />

### Histogram of Transaction Amounts
<img width="857" height="451" alt="image" src="https://github.com/user-attachments/assets/c8d8ec90-3bbd-46d8-9cc2-3c07182297ba" />

### Fraud vs Non-Fraud Pie Chart
<img width="481" height="504" alt="image" src="https://github.com/user-attachments/assets/98e27a60-680a-4ee1-b5b2-4da834da04f6" />

### Average Transaction Amount Comparison
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/235ff3c5-22a0-48dd-9857-8d79c60de6c1" />

### Transaction Amount Distribution (Log Scale)
<img width="694" height="470" alt="image" src="https://github.com/user-attachments/assets/a239e800-2e0e-43d1-9c0b-445463d3ccdb" />

### Feature Correlation Heatmap
<img width="816" height="722" alt="image" src="https://github.com/user-attachments/assets/a8e66607-a7c6-43e1-9acc-65d2053cc338" />

---

## 📝 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/CreditCard-Fraud-Analysis.git
