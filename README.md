# ASD Detection System — AI-Powered Autism Screening and Prediction

![ASD Detection](https://img.shields.io/badge/ASD%20Detection-v1.0-2563eb?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square\&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Latest-FF4B4B?style=flat-square\&logo=streamlit)
![Scikit--Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=flat-square\&logo=scikitlearn)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Training-F9AB00?style=flat-square\&logo=googlecolab)

---

## Overview

The ASD Detection System is an AI-powered screening platform designed to predict Autism Spectrum Disorder (ASD) traits using behavioral and screening data. The system combines machine learning classification with feature optimization techniques to provide accurate and efficient predictions.

This project uses **Support Vector Machine (SVM)** as the primary prediction model and applies the **Butterfly Optimization Algorithm (BOA)** for feature selection. A modern **Streamlit web application** is integrated to allow users to complete screening questionnaires and receive instant results.

The platform is intended for awareness, educational use, and early screening support.

---

## What This Project Delivers

* Early ASD trait screening through an interactive web platform
* Machine learning-based prediction using optimized features
* Real-time results from user responses
* Self Screening and Observer Screening modes
* Child-friendly and adult-friendly questionnaire flows
* Support and awareness guidance after screening
* Clean and responsive user interface

---

## System Workflow

```text
User Input (Questionnaire)
          ↓
   Data Collection Layer
          ↓
   Data Preprocessing
   - Missing Value Handling
   - Encoding
   - Feature Scaling
          ↓
Feature Selection using BOA
          ↓
Model Training using SVM
          ↓
Prediction Engine
          ↓
Streamlit Frontend Output
```

---

## Core Modules

## 1. Data Preprocessing

The dataset is cleaned and transformed before training.

* Missing values replaced using statistical methods
* Categorical values encoded into numerical form
* Features standardized using scaling techniques
* Train-test split applied for evaluation

---

## 2. Feature Selection using BOA

The Butterfly Optimization Algorithm is used to identify the most relevant features from the dataset.

Benefits:

* Reduces unnecessary input variables
* Improves model efficiency
* Enhances prediction quality
* Minimizes computational complexity

---

## 3. Machine Learning Models Evaluated

Multiple models were tested for comparison.

| Model                        | Accuracy |
| ---------------------------- | -------- |
| Support Vector Machine (SVM) | 99.49%   |
| K-Nearest Neighbors (KNN)    | 97.48%   |
| Logistic Regression          | 96.97%   |
| Random Forest                | 100.00%  |

**Selected Model:** Support Vector Machine (SVM)
SVM was chosen for deployment because of its strong generalization ability and reliable classification performance.

---

## 4. Frontend Application

The system includes a Streamlit-based interface for easy interaction.

### Key Features

* Home page with guided navigation
* Self Screening mode
* Observer Screening mode
* Adaptive questionnaire based on age group
* Instant prediction result page
* Awareness and support resources
* Responsive design for desktop and mobile use

---

## Tools and Technologies Used

| Layer                | Technology                              |
| -------------------- | --------------------------------------- |
| Programming Language | Python                                  |
| Data Processing      | Pandas, NumPy                           |
| Visualization        | Matplotlib, Seaborn                     |
| Machine Learning     | Scikit-learn                            |
| Optimization         | Butterfly Optimization Algorithm        |
| Frontend             | Streamlit                               |
| Development Platform | Google Colab, VS Code, Jupyter Notebook |

---

## Project Structure

```text
ASD-Detection-System/
├── app.py                 # Streamlit frontend application
├── training.ipynb         # Model training and evaluation
├── data_csv.csv           # Dataset
├── model.pkl              # Saved trained model
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## Installation Guide

## Step 1 — Clone Repository

```bash
git clone https://github.com/your-username/asd-detection-system.git
cd asd-detection-system
```

## Step 2 — Install Requirements

```bash
pip install -r requirements.txt
```

## Step 3 — Run Application

```bash
streamlit run app.py
```

---

## Performance Evaluation Metrics

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics ensure reliable classification performance across test samples.

---

## Future Enhancements

* Explainable AI dashboard
* Cloud deployment
* Mobile application version
* Multi-language support
* Specialist recommendation module
* Database integration for user reports
* Advanced analytics and visualization

---

## Disclaimer

This system is developed for educational purposes and early ASD screening support only. It is not a medical diagnostic tool. Professional healthcare consultation is recommended for formal diagnosis.

---

## Author

Shahnas M
Mekha S R
Rinu Antony
BTech Artificial Intelligence and Machine Learning

---

## Summary

The ASD Detection System combines intelligent prediction, optimization techniques, and an accessible web interface to support early autism awareness and screening.

**Accurate, accessible, and user-friendly AI-powered ASD screening.**
