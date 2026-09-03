# OIBSIP
Data Science Internship Projects — Oasis Infobyte (OIBSIP)
# Iris Flower Classification (OIBSIP Task 1)

This repository contains the implementation for **Task 1: Iris Flower Classification** as part of the Oasis Infobyte Data Science Internship (OIBSIP).

## 📌 Project Overview
The objective of this project is to build a Machine Learning model that accurately classifies Iris flowers into three species based on their measurements:
- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

Using the classic Iris dataset, we performed Exploratory Data Analysis (EDA) and trained a **Random Forest Classifier** to achieve **100% classification accuracy**.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas` — Data manipulation and analysis
  - `matplotlib` & `seaborn` — Data visualization
  - `scikit-learn` — Model training, evaluation, and train-test splitting

---

## 📊 Workflow & Implementation
1. **Data Loading & Inspection**: Loaded the Iris dataset, checked data structure using `df.info()`, `df.describe()`, and evaluated class distributions.
2. **Exploratory Data Analysis (EDA)**: Visualized feature relationships across species using Seaborn pair plots.
3. **Data Preprocessing**: Separated features (`X`) and target labels (`y`), followed by an **80/20 train-test split** (`random_state=42`).
4. **Model Training**: Trained a `RandomForestClassifier(random_state=42)` model on the 120 training samples.
5. **Evaluation**: Tested performance on 30 held-out samples, achieving an **accuracy score of 1.0 (100%)** across precision, recall, and F1-score.
6. **Inference**: Tested predictions on custom, unseen sample measurements.

---

## 📈 Model Performance
```text
Accuracy: 1.0 (100%)

Classification Report:
              precision    recall  f1-score   support
      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11
