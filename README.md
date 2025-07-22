# 🛡️ NETOPTAI: ML-Powered Phishing Website Detection System

**NETOPTAI** is an intelligent, modular system that detects phishing websites using machine learning. Designed with MLOps best practices, it supports scalable data ingestion using MongoDB, rigorous hyperparameter tuning with GridSearchCV, and robust experiment tracking through MLflow.

---

## 🚀 Features

- 🔍 **Phishing Website Detection** using ML classifiers (Random Forest, Decision Tree, etc.)
- 🛢️ **Data Ingestion from MongoDB** for scalable, real-world integration
- 📊 **MLflow Tracking** for experiment reproducibility
- 🧠 **GridSearchCV** for optimal model performance
- 🔧 Modular MLOps-friendly structure for production workflows

---

## 🧠 Tech Stack

| Category        | Technology               |
|----------------|--------------------------|
| Language        | Python                   |
| ML Models       | RandomForest, DecisionTree, etc. |
| Tuning          | GridSearchCV (scikit-learn) |
| Tracking        | MLflow                   |
| Data Ingestion  | MongoDB                  |
| Deployment Ready| Modular, Testable Design |

---

## 📁 Project Structure


NETOPTAI/
│
├── networksecurity/
│ ├── model.py # Training + GridSearchCV + MLflow logging
│ ├── preprocess.py # MongoDB data ingestion + cleaning
│ └── utils.py # Reusable helper functions
│
├── final_model/ # Serialized production-ready models
├── data/ # Static datasets (optional)
├── mlruns/ # MLflow experiment logs (auto-generated)
│
├── app.py # Application entrypoint
├── test_mongodb.py # MongoDB connection sanity test
├── requirements.txt # Project dependencies
└── README.md # This file

