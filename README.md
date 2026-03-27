# Behavioral-risk

# 🏦 Behavioral Risk Prediction in Banking

## 📌 Business Problem

In the banking industry, identifying high-risk customers early is critical to prevent financial losses, fraud, and poor credit decisions.
However, traditional rule-based systems often fail to capture complex behavioral patterns in customer transactions.

---

## 🎯 Project Objective

This project aims to build a **machine learning system** that predicts customer behavioral risk based on transaction and user data, enabling banks to make **data-driven risk management decisions**.

---

## 💼 Business Impact

* 🔍 Early detection of high-risk customers
* 💸 Potential reduction in financial losses due to fraud or bad credit
* ⚡ Improved efficiency in risk assessment processes
* 📊 Support for better decision-making in customer management

---

## 📂 Dataset

The project integrates multiple data sources:

* **User data** (demographics, profiles)
* **Transaction data** (spending behavior)
* **Card data**
* **MCC codes** (merchant categories)

---

## ⚙️ Methodology

### 1. Data Processing

* Data cleaning and merging from multiple sources
* Feature engineering from transaction patterns
* Train/validation/test split

### 2. Modeling

Several models were trained and compared:

* Logistic Regression
* Random Forest
* XGBoost

### 3. Model Selection

* Hyperparameter tuning applied
* Best model selected based on performance metrics

---

## 📊 Model Output

* Final trained model: `final_model_artifact.pkl`
* Additional tuned models stored for comparison

---

## 📁 Project Structure

```
BANKING/
│── Code Python/
│   ├── Data.ipynb
│   ├── Train.ipynb
│   ├── model files (.pkl)
│   ├── datasets (.csv)
│
│── Data/
│   ├── raw data (.xlsx)
```

---

## ▶️ How to Run

```bash
git clone https://github.com/HoangDuyQuang/Behavioral-Risk.git
cd Behavioral-Risk
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebooks:

* Open `Train.ipynb`
* Execute all cells

---

## 📈 Key Skills Demonstrated

* Data preprocessing & feature engineering
* Machine learning model development
* Model evaluation & tuning
* Handling real-world structured data

---

## 🔮 Future Improvements

* Deploy model as API or web app (Streamlit/FastAPI)
* Add real-time prediction pipeline
* Improve feature engineering from transaction sequences

---

## 👨‍💻 Author

**Hoang Duy Quang**

---

## ⭐ Note

This project is developed for learning and portfolio purposes in the field of Data Science and Machine Learning.
