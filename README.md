# 📱 SmartPhone Guard

<p align="center">

# Machine Learning-Based Early Detection System for Smartphone Addiction

A web-based application that predicts smartphone addiction levels using Machine Learning algorithms and Flask.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

</p>

---

# 📖 Overview

SmartPhone Guard is a Machine Learning-powered web application designed to detect the risk level of smartphone addiction based on users' digital behavior.

The system analyzes user activity patterns through several behavioral features and predicts addiction levels into three categories:

- Mild Addiction
- Moderate Addiction
- Severe Addiction

This project integrates Machine Learning classification models into a Flask web application, allowing users to perform real-time predictions through an intuitive interface.

---

# 🎯 Objectives

The objectives of this project are:

- Analyze smartphone usage behavior.
- Build Machine Learning classification models.
- Compare multiple algorithms.
- Improve model performance using Hyperparameter Optimization (HPO).
- Handle imbalanced datasets using SMOTE.
- Deploy the best-performing model into a Flask web application.

---

# 📂 Dataset

**Dataset**

Digital Habits & Smartphone Addiction Dataset

**Source**

https://www.kaggle.com/datasets/guriya79/smart-phone

### Features

- Age
- Gender
- Daily Screen Time
- Social Media Hours
- Gaming Hours
- Work/Study Hours
- Sleep Hours
- Notifications Per Day
- App Opens Per Day
- Weekend Screen Time

### Target

- Mild Addiction
- Moderate Addiction
- Severe Addiction

---

# 🤖 Machine Learning Algorithms

This project compares four Machine Learning classification algorithms:

- 🌳 Decision Tree
- ⚡ Support Vector Machine (SVM)
- 👥 K-Nearest Neighbor (KNN)
- 🧠 Neural Network (MLPClassifier)

---

# 🔄 Machine Learning Pipeline

```text
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Encoding
      │
      ▼
SMOTE
      │
      ▼
Train-Test Split
      │
      ▼
Hyperparameter Optimization
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Best Model Selection
      │
      ▼
Flask Web Deployment
```

---

# 📊 Model Performance

| Algorithm | Before HPO | After HPO |
|-----------|-----------:|----------:|
| Decision Tree | 54.90% | **57.74%** |
| SVM | 54.53% | 56.02% |
| K-Nearest Neighbor | 53.24% | 55.27% |
| Neural Network | 54.53% | 56.02% |

**Best Model**

🏆 Decision Tree

Accuracy after Hyperparameter Optimization:

**57.74%**

---

# ✨ Features

## User

- Register
- Login
- Predict Smartphone Addiction
- Upload CSV Dataset
- Prediction History
- Search Prediction History
- Download Prediction Results

## Admin

- Dashboard
- Manage Users
- Retrain Machine Learning Model
- Manage Prediction History
- View Prediction Statistics

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Flask | Backend Framework |
| Scikit-learn | Machine Learning |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| HTML | Frontend |
| CSS | Styling |
| JavaScript | Client-side Interaction |
| SQLite | Database |

---

# 📁 Project Structure

```text
SmartPhone-Guard
│
├── dataset-notebook
├── model
├── smartaddict
├── static
├── templates
│
├── app.py
├── requirements.txt
├── prediction_history.json
└── README.md
```

---

# 🚀 Installation

Clone repository

```bash
git clone https://github.com/Khuzaivan/SmartPhone-Guard.git
```

Move into project

```bash
cd SmartPhone-Guard
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate Environment

Windows

```bash
venv\Scripts\activate
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run Application

```bash
python app.py
```

---

# 👨‍💻 My Contributions

As one of the developers in this academic Machine Learning project, I contributed to:

- Developed the Flask-based web application.
- Implemented Machine Learning integration into the prediction system.
- Built prediction workflow and history management.
- Implemented user authentication and prediction features.
- Assisted in data preprocessing and feature preparation.
- Participated in implementing Decision Tree, SVM, KNN, and Neural Network models.
- Assisted in Hyperparameter Optimization (HPO) and model evaluation.
- Contributed to testing, debugging, project documentation, and presentation.

---

# 📈 Results

✔ Successfully built an end-to-end Machine Learning web application.

✔ Compared four Machine Learning classification algorithms.

✔ Applied Hyperparameter Optimization (HPO).

✔ Used SMOTE to balance class distribution.

✔ Integrated the best-performing model into a Flask application.

✔ Decision Tree achieved the highest accuracy (57.74%).

---

# 📸 Screenshots

## Home Page

Coming Soon

## Login

Coming Soon

## Prediction Page

Coming Soon

## Prediction Result

Coming Soon

## Prediction History

Coming Soon

## Admin Dashboard

Coming Soon

---

# 👥 Team Members

- Khuzaivan Ryandiezca Erlangga
- Muhammad Abyaz Zaydan
- Muhammad Zaqi Zallul

---

# 🔮 Future Improvements

- Deep Learning Model
- REST API
- Docker Deployment
- Cloud Deployment
- Mobile Responsive UI
- User Dashboard Analytics
- Model Explainability (SHAP/LIME)

---

# 📄 License

This project was developed for academic and educational purposes.