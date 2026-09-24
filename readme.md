# ❤️ PulsePredict — Clinical Risk Analyzer

PulsePredict is an end-to-end Machine Learning project that predicts cardiovascular disease risk from patient health information.

The project demonstrates the complete ML workflow:

**Data → Cleaning → EDA → Preprocessing → Model Training → Evaluation → Streamlit Application → Deployment**

> ⚠️ **Disclaimer:** PulsePredict is an educational machine-learning prototype. It is not a medical diagnostic system and should not be used for real clinical decision-making.

---

## 🚀 Live Demo

**Hugging Face Space:**  
Add your deployed Hugging Face URL here.

Example:

`https://huggingface.co/spaces/YOUR_USERNAME/PulsePredict`

---

## 📌 Project Overview

Healthcare datasets contain many patient attributes such as age, blood pressure, cholesterol, chest pain type, and maximum heart rate.

The goal of PulsePredict is to demonstrate how these features can be processed by machine-learning models to produce a predicted cardiovascular-risk classification.

The application allows a user to enter patient information through a Streamlit interface and receive:

- Predicted risk probability
- YES/NO model prediction
- Interactive patient input interface

The project is designed primarily to demonstrate **machine-learning engineering and model deployment**, rather than clinical diagnosis.

---

# 🎯 Objectives

The main objectives of this project are:

- Understand a real-world healthcare dataset
- Perform exploratory data analysis
- Clean missing and duplicate data
- Separate features and target
- Perform train/test splitting
- Apply appropriate preprocessing
- Handle numerical and categorical features
- Train classification models
- Evaluate classification performance
- Create a reusable Scikit-learn pipeline
- Build an interactive Streamlit application
- Deploy the application publicly

---

# 🧠 Machine Learning Approach

The project uses two classification algorithms:

### 1. Logistic Regression

Used as the baseline classification model.

Advantages:

- Simple
- Fast
- Easy to interpret
- Provides probability estimates

### 2. Random Forest

Used as the tree-based classification model.

Advantages:

- Handles nonlinear relationships
- Works well with mixed feature types after preprocessing
- Provides feature importance
- Produces probability estimates

---

# 📊 Dataset

The project uses the **UCI Heart Disease dataset**.

Dataset characteristics used in this project:

- **303 patient records**
- **13 input features**
- **1 target variable**

### Features

| Feature | Description |
|---|---|
| `age` | Age of the patient |
| `sex` | Sex |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol |
| `fbs` | Fasting blood sugar |
| `restecg` | Resting electrocardiographic result |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression |
| `slope` | Slope of peak exercise ST segment |
| `ca` | Number of major vessels |
| `thal` | Thalassemia-related category |

### Target

```text
0 → Negative class
1 → Positive class