# 🔍 Task 4: Classification with Logistic Regression - Elevate AI/ML Internship

## 🎯 Objective

To build a binary classifier using logistic regression and evaluate it using metrics like precision, recall, ROC-AUC, and confusion matrix.

---

## 📁 Dataset

**Breast Cancer Wisconsin Dataset**  
🔗 [Kaggle Link]
(https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn

---

## 📈 Workflow

### 1. Data Preprocessing

- Dropped `id` and `Unnamed: 32` columns.
- Encoded target column `diagnosis` (Malignant=1, Benign=0).
- Standardized features using `StandardScaler`.

### 2. Model Building

- Used `LogisticRegression` from `sklearn.linear_model`.
- Train/test split (80/20).
- Fitted model on training data.

### 3. Model Evaluation

- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1)
- **ROC-AUC Score**
- **ROC Curve** Visualization

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Accuracy | 97%  |
| ROC AUC | 1.00 |
| Precision | 95% |
| Recall | 98% |

> The model performed well in distinguishing malignant vs benign cases.

---

## 📎 File Structure

├── data.csv

├── Task4.ipynb

├── README.md
