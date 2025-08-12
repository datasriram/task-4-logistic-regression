# task-4-logistic-regression
Logistic Regression Binary Classification on Heart Disease dataset using Python.
# Task 4 – Logistic Regression (Heart Disease Prediction)

## 📌 Project Overview
This project implements **Logistic Regression** to predict whether a patient has heart disease based on various medical attributes.  
The model is trained on the **Heart Disease Dataset** and demonstrates a binary classification approach using Python's `scikit-learn`.

---

## 📂 Dataset
- **Source:** [Kaggle – Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **File:** `heart.csv`
- **Target Column:** `target`  
  - `1` → Heart disease present  
  - `0` → No heart disease

---

## 🛠️ Steps Performed
1. **Data Loading** – Loaded the dataset from GitHub.
2. **Data Exploration** – Checked structure, missing values, and statistical summary.
3. **Data Preprocessing** –  
   - Split dataset into features (`X`) and target (`y`)
   - Standardized numerical features using `StandardScaler`
4. **Model Training** – Trained Logistic Regression model using `scikit-learn`.
5. **Model Evaluation** –  
   - **Confusion Matrix**
   - **Classification Report** (Precision, Recall, F1-score)
   - **ROC Curve** with AUC score
6. **Visualization** – Plotted confusion matrix and ROC curve.

---

## 📊 Results
- **Evaluation Metrics:**
  - Accuracy: *~85–90%* (varies slightly due to train/test split)
  - High Precision & Recall for both classes
- **Visuals:**
  - Confusion Matrix Heatmap
  - ROC Curve with AUC score

---

## 📦 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/datasriram/task-4-logistic-regression.git
