# Data Science Task 4: Email Spam Detection with Machine Learning

## Project Overview
This project builds a Natural Language Processing (NLP) binary classification model to detect whether an email or SMS message is **Spam** or **Ham** (legitimate).

## Workflow & Methodology
- **Data Cleaning:** Removed duplicates and null values, and mapped string targets (`ham`, `spam`) to binary values (`0`, `1`).
- **Feature Extraction:** Converted raw text into numerical feature vectors using `TfidfVectorizer` with stop-word removal.
- **Model Training:** Trained a Naive Bayes (`MultinomialNB`) algorithm suited for text classification tasks.
- **Evaluation:** Assessed performance using accuracy scores, detailed classification metrics, a confusion matrix heatmap, and custom message inference tests.

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## How to Run
1. Clone this repository.
2. Ensure `spam.csv` (or the extracted dataset) is placed in the project directory.
3. Open `Email_Spam_Detection.ipynb` in Jupyter Notebook and execute all cells sequentially.