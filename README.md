Credit Card Fraud Detection

A. Project Overview
This project demonstrates:
1. Loading and exploring a **highly imbalanced fraud dataset**
2. Visualizing **class distributions** before and after balancing
3. Balancing the dataset using **undersampling**
4. Preprocessing (scaling `Time` and `Amount` features)
5. Training a **Logistic Regression Classifier**
6. Evaluating using **accuracy** 

B. Project Structure

fraud-detection/
│
├── Credit Card Fraud Detection.ipynb   # Main Jupyter notebook
├── creditcard.csv                      # Dataset (to be added locally)
├── requirements.txt                    # Project dependencies
└── README.md                           # Project documentation


C. Dataset

1. Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
2. Details:
  a. 284,807 transactions
  b. 492 fraud cases (\~0.17% fraud)
  c.Features: `V1`–`V28` (PCA-transformed), `Amount`, `Time`, `Class` (target)

D. Workflow

1️. Install Required Libraries:
   pip install numpy pandas matplotlib seaborn scikit-learn

2️. Load Dataset:
  View shape and head of the dataset

3️. Class Distribution Visualization:
  Plot fraud vs. non-fraud counts using `seaborn`

4️. Class Balancing:
  Undersampling: Sample the non-fraud class to match fraud class count

5️. Preprocessing:
  Scale `Time` and `Amount` using `StandardScaler`

6️. Train/Test Split:
   80% training, 20% testing split

7️. Model Training:
   Train a **Logistic Regression Classifier**

8️. Evaluation:
  Print **accuracy score**

E. Learning

1. Handling **imbalanced datasets** using **undersampling**
2. Feature scaling for numeric features
3. Training a **baseline ML model (Logistic Regression)**
4. Basic evaluation with accuracy for classification tasks

