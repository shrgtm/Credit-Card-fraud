
# 💳 Credit Card Fraud Detection – Exploratory Data Analysis (EDA)

## 🚀 Project Overview  
Ever wondered how **banks detect fraudulent transactions**? In this project, we’ll explore a **real-world dataset** of credit card transactions to uncover hidden patterns in fraudulent activities.  

Using **Exploratory Data Analysis (EDA)**, we’ll visualize trends, detect anomalies, and gain insights into how fraud works. The goal is to **understand the data better** so we can later train an AI model to catch fraudsters in action!  

---

## 📂 About the Dataset  
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets)  
- **Total Transactions**: **284,807**  
- **Features**: 30 (`V1` to `V28`, `Time`, `Amount`, `Class`)  
- **Class Labels**:  
  - `0` → **Legitimate Transactions**  
  - `1` → **Fraudulent Transactions**  
- **Key Challenge**:  
  - This dataset is **highly imbalanced** → **99.83% legit transactions** vs. **0.17% fraud cases**  
  - This makes fraud detection tricky!  

---

## 🛠️ How to Run This Project  
### **Step 1: Install the required libraries**  
Make sure you have Python and these libraries installed:  
```bash
pip install pandas numpy matplotlib seaborn
```
### **Step 2: Load the dataset into Python**  

📌 **What’s Interesting?**  
- Some PCA-transformed features **show clear separation between fraud & non-fraud** transactions.  
- Even though we **don’t know what V1, V2, V3 mean**, they **help AI models detect fraud**.  

---

 **Key Takeaways**
✅ **Fraud is rare**, so detecting it is **challenging**.  
✅ **Fraudulent transactions can happen anytime** – no fixed time pattern.  
✅ **High transaction amounts could be risky**, but not always fraud.  
✅ **Some PCA features (V1-V28) clearly separate fraud cases** – useful for AI models.  

---

## 🚀 **Next Steps: What’s Next?**  
🔹 Train **Machine Learning models** to automatically detect fraud.  
🔹 Use **oversampling techniques** like **SMOTE** to balance the dataset.  
🔹 Deploy a **fraud detection system** to catch fraud in real-time!  

---

