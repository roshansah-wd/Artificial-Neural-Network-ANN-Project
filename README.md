# Artificial-Neural-Network-ANN-Project
# 🏦 Customer Churn Prediction using Artificial Neural Networks (ANN)

A deep learning project that predicts whether a bank customer is likely to leave the bank (churn) based on customer demographics and account information. The model is built using TensorFlow/Keras and deployed with Streamlit for real-time predictions.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for banks and financial institutions. This project uses an **Artificial Neural Network (ANN)** to predict whether a customer will churn based on historical customer data.

The application allows users to input customer information and instantly receive a churn prediction with the probability of the customer leaving the bank.

---

## 🎯 Objectives

- Predict customer churn using an ANN model.
- Perform data preprocessing and feature engineering.
- Train and evaluate a deep learning model.
- Deploy the model using Streamlit.
- Provide real-time churn predictions.

---

## 📂 Dataset

The project uses the **Churn Modelling Dataset**.

### Features

| Feature | Description |
|----------|-------------|
| CreditScore | Customer's credit score |
| Geography | Customer's country |
| Gender | Male/Female |
| Age | Customer age |
| Tenure | Number of years with the bank |
| Balance | Bank account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Whether customer has a credit card |
| IsActiveMember | Whether customer is an active member |
| EstimatedSalary | Estimated annual salary |

### Target Variable

| Value | Meaning |
|-------|---------|
| 0 | Customer stays |
| 1 | Customer churns |

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Pickle

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── app.py                      # Streamlit application
├── model.h5                    # Trained ANN model
├── scaler.pkl                  # StandardScaler
├── label_encoder_gender.pkl    # Label Encoder
├── onehot_encoder_geo.pkl      # OneHot Encoder
├── Churn_Modelling.csv         # Dataset
├── experiments.ipynb           # Model development notebook
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
```

---

## ⚙️ Workflow

### 1. Data Collection

- Load the customer churn dataset.
- Explore data and understand feature distributions.

### 2. Data Preprocessing

- Remove unnecessary columns.
- Encode categorical variables.
- Scale numerical features.
- Split data into training and testing sets.

### 3. Model Building

Artificial Neural Network architecture:

- Input Layer
- Hidden Layer (ReLU)
- Hidden Layer (ReLU)
- Output Layer (Sigmoid)

### 4. Model Training

- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy

### 5. Model Evaluation

The model is evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- ROC-AUC (optional)

### 6. Deployment

The trained model is deployed using **Streamlit**, allowing users to interact with the model through a web interface.

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Move into the project folder

```bash
cd customer-churn-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📊 Model Inputs

The user provides:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

---

## 📈 Output

The model predicts:

- **Customer Will Stay**
- **Customer Will Churn**

It also provides the churn probability.

---

## 🧠 Machine Learning Pipeline

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Encoding
    │
    ▼
Feature Scaling
    │
    ▼
Train-Test Split
    │
    ▼
Artificial Neural Network
    │
    ▼
Model Evaluation
    │
    ▼
Save Model & Encoders
    │
    ▼
Streamlit Deployment
```

---

## 📌 Future Improvements

- Hyperparameter tuning
- Early stopping
- Dropout regularization
- Cross-validation
- SHAP for model explainability
- Docker containerization
- Cloud deployment (AWS, Azure, or Google Cloud)

---

## 📷 Application Preview
<img width="1237" height="857" alt="Screenshot 2026-07-28 224147" src="https://github.com/user-attachments/assets/82aaf75d-8734-405c-8aca-523118e26198" />
<img width="1022" height="707" alt="Screenshot 2026-07-28 224210" src="https://github.com/user-attachments/assets/06d58a4d-378e-4669-816a-a3970548eea5" />



Home Page

Prediction Result

Probability Output
```
## 📚 Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- Artificial Neural Networks
- Deep Learning
- TensorFlow/Keras
- Model Evaluation
- Streamlit Deployment
- Machine Learning Workflow

## ⭐ If you found this project useful, consider giving it a star!
