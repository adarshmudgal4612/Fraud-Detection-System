# Financial Transaction Fraud Detection System

A Machine Learning–based fraud detection system developed to identify suspicious financial transactions using transaction-level behavioral patterns and balance analysis. The project leverages a dataset containing 6.3M+ transaction records and provides real-time fraud prediction through an interactive Streamlit web application.

---

## Features

- Fraud prediction using Logistic Regression
- Real-time transaction analysis through Streamlit UI
- Exploratory Data Analysis (EDA) and fraud pattern visualization
- Feature engineering using sender/receiver balance differences
- Preprocessing pipeline using Scikit-learn Pipeline and ColumnTransformer
- One-hot encoding and feature scaling for robust model training

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit
- Joblib

---

## Dataset

The dataset contains over **6.3 million financial transaction records** with transaction types such as:

- PAYMENT
- TRANSFER
- CASH_OUT
- DEPOSIT

The objective is to classify transactions as **fraudulent** or **non-fraudulent**.

---

## Model Workflow

1. Data Cleaning and Exploratory Data Analysis
2. Feature Engineering
3. Data Preprocessing using `StandardScaler` and `OneHotEncoder`
4. Model Training using `Logistic Regression`
5. Pipeline Serialization using `Joblib`
6. Streamlit-based Deployment

---

## Results

- Achieved approximately **95% accuracy** on test data
- Successfully identified suspicious transaction behavior patterns
- Built an end-to-end deployable fraud detection pipeline

---

## Project Structure

```bash
├── fraud_detection_pipeline.pkl
├── requirements.txt
├── analysis_model.ipynb
├── AI/ML dataset.csv
├── Fruad_Detection.py
└── README.md
```

---

## Run Locally

Clone the project:

```bash
git clone https://github.com/adarshmudgal4612/fraud-detection-system.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run fraud_detection.py
```

---

## Future Improvements

- Experiment with advanced models such as XGBoost and Random Forest
- Improve fraud recall using ensemble techniques
- Add transaction history–based anomaly detection

---

## Author

**Adarsh Mudgal**
