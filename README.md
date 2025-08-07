# 🍷 Wine Quality Prediction and Classification

This project builds a **machine learning model** to predict and classify the **quality of red wine** using physicochemical features. It uses the UCI Wine Quality Dataset.

---

## 📂 Dataset

- Source: [UCI Machine Learning Repository – Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- File used: `winequality-red.csv`
- Number of records: 1599
- Features: 11 (like acidity, alcohol, pH)
- Target: Wine quality (converted to `Low`, `Medium`, `High` categories)

---

## 🧠 Models Used

- `RandomForestClassifier` (Primary)
- Scikit-learn's preprocessing and evaluation tools

---

## 📌 Features

- Loads dataset directly from UCI
- Maps numeric quality score to 3 classes:
  - `Low` (3–4)
  - `Medium` (5–6)
  - `High` (7–8)
- Feature scaling with `StandardScaler`
- Model training and testing using `train_test_split`
- Evaluation:
  - Classification report (Precision, Recall, F1-score)
  - Confusion matrix (plotted using Seaborn)

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername


              precision    recall  f1-score   support

         High       0.89      0.67      0.76        33
          Low       0.90      0.56      0.69        27
       Medium       0.85      0.97      0.90       260

    accuracy                           0.86       320
   macro avg       0.88      0.73      0.78       320
weighted avg       0.86      0.86      0.85       320
