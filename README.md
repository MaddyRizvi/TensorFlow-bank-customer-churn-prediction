# 🧠 Customer Churn Prediction with Artificial Neural Network

This project uses an Artificial Neural Network (ANN) built with TensorFlow to predict whether a customer will leave a bank (churn). The model is trained on the `Churn_Modelling.csv` dataset, which contains various customer attributes such as geography, gender, age, balance, etc.

## 📌 Project Overview

- **Problem**: Predict customer churn using historical banking data.
- **Solution**: A classification model using a deep learning ANN.
- **Model Framework**: TensorFlow/Keras with Scikit-learn for preprocessing.

## 📁 Repository Structure

```
.
├── Churn_Modelling.csv         # Dataset
├── artificial_neural_network.py     # Main Python script to run the model
├── README.md                   # Project overview and setup instructions
└── requirements.txt            # Python dependencies
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/MaddyRizvi/TensorFlow-bank-customer-churn-prediction.git
cd TensorFlow-bank-customer-churn-prediction
```

### 2. Install dependencies

It's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the model

Make sure the dataset (`Churn_Modelling.csv`) is in the root directory. Then run:

```bash
python TensorFlow-bank-customer-churn-prediction.py
```

This script will preprocess the data, build and train the ANN, and display evaluation results.

## 🧾 Requirements

The main libraries used include:

- Python 3.7+
- TensorFlow
- Pandas
- NumPy
- Scikit-learn

You can install all requirements using:

```bash
pip install -r requirements.txt
```

## 📊 Dataset

The dataset contains information about 10,000 customers including:
- Geography
- Gender
- Credit Score
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Churn (target variable)

## 📈 Model Highlights

- ANN with two hidden layers using ReLU activation.
- Output layer uses sigmoid activation for binary classification.
- Accuracy and confusion matrix used for evaluation.

## 🤔 How to Use the Model

- After training, the model can be used to predict whether a new customer will churn based on their features.
- Example usage is included in the script for a single customer prediction.

## 📌 Note

Ensure your input data for predictions follows the same preprocessing pipeline used during training (especially feature scaling and encoding).

## 📫 Contact

For questions or suggestions, feel free to open an issue or contact [mohsinrizvi.dgk@gmail.com](mailto:mohsinrizvi.dgk@gmail.com).
