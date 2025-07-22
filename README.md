# 💳 Fraud Detection using Transaction Data & Machine Learning

This project builds a supervised machine learning model to detect fraudulent financial transactions based on features like transaction type, amount, balances, and origin/destination accounts.

---

## 📌 Project Overview

Fraud detection in financial transactions is crucial for banks, payment processors, and e-commerce platforms. In this project, we use a synthetic dataset to train models that classify transactions as **fraudulent** or **genuine**.

---

## 🧠 Technologies Used

* **Python 3.x**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Data visualization
* **Scikit-learn** – Machine Learning (Logistic Regression, Random Forest, etc.)
* **Jupyter Notebook** – Exploratory Analysis and Model Training

---

## 📊 Dataset Details

Each row in the dataset represents a single transaction with the following fields:

| Feature          | Description                                 |
| ---------------- | ------------------------------------------- |
| `step`           | Time step of the transaction                |
| `type`           | Transaction type (e.g., CASH\_OUT, PAYMENT) |
| `amount`         | Amount transferred                          |
| `nameOrig`       | Sender's account ID                         |
| `oldbalanceOrg`  | Sender's balance before the transaction     |
| `newbalanceOrg`  | Sender's balance after the transaction      |
| `nameDest`       | Receiver's account ID                       |
| `oldbalanceDest` | Receiver's balance before the transaction   |
| `newbalanceDest` | Receiver's balance after the transaction    |
| `isFraud`        | Target variable (0 = Legit, 1 = Fraud)      |

Sample Data:

| type      | amount  | oldbalanceOrg | newbalanceOrg | isFraud |
| --------- | ------- | ------------- | ------------- | ------- |
| CASH\_OUT | 7206.53 | 10670.17      | 6620.76       | 0       |
| DEBIT     | 4450.35 | 16469.06      | 12713.29      | 0       |
| PAYMENT   | 1912.23 | 8220.85       | 6275.55       | 0       |

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Open and run the notebook**

   * Open `fraud_detection.ipynb` in Jupyter Notebook or VS Code
   * Execute cells sequentially

---

## 📈 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision, Recall, F1 Score
* ROC AUC Curve

---

## 🔍 Key Features

✅ Clean and process transactional data
✅ Visualize transaction types and fraud distribution
✅ Train & evaluate classification models
✅ Identify important fraud indicators

---

## 📌 Future Scope

* Implement anomaly detection with unsupervised learning
* Train a deep learning model (LSTM or Autoencoder)
* Deploy the model using Flask or Streamlit for real-time predictions

---

## 🙏 Acknowledgements

* Scikit-learn, Pandas, Seaborn
* Synthetic dataset based on financial transactions
* Inspired by real-world fraud detection challenges

