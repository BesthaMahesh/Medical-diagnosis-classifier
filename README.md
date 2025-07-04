# 🩺 Medical Diagnosis Classifier with Logistic Regression

A machine learning project to predict the likelihood of a medical condition (e.g., diabetes) based on patient health indicators using **Logistic Regression**.

---

## 💡 Project Description

This project builds a **binary classification model** that predicts whether a patient is likely to have a medical condition using features such as:

- **Age**
- **Glucose Level**
- **BMI (Body Mass Index)**
- **Blood Pressure**

We use **Logistic Regression** to perform classification and evaluate the model using:

- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## 📁 Dataset

A **simulated dataset** is created with the following columns:

| Feature         | Description                      |
|----------------|----------------------------------|
| Age            | Patient's age (years)            |
| Glucose        | Glucose level                    |
| BMI            | Body Mass Index                  |
| BloodPressure  | Blood pressure (mm Hg)           |
| Condition      | Target label (1 = Yes, 0 = No)   |

---

## 🧪 Tech Stack

- Python 3
- pandas – Data manipulation
- numpy – Numerical operations
- scikit-learn – ML model and evaluation
- matplotlib & seaborn – Visualization

---

## ⚙️ How It Works

1. **Data Preparation**
   - Created a simulated DataFrame
   - Split features and target (`Condition`)

2. **Preprocessing**
   - Applied `StandardScaler` to normalize input features

3. **Model Training**
   - Trained a `LogisticRegression` model on training data

4. **Evaluation**
   - Generated a classification report
   - Plotted a confusion matrix
   - Calculated ROC-AUC score

---

## 📊 Output Example

```
Classification Report:
              precision    recall  f1-score   support

           0       1.00      0.67      0.80         3
           1       0.75      1.00      0.86         3

    accuracy                           0.83         6
   macro avg       0.88      0.83      0.83         6
weighted avg       0.88      0.83      0.83         6

ROC-AUC Score: 0.94
```

---

## 📌 Key Learnings

- Understanding logistic regression for binary classification  
- Importance of feature scaling using StandardScaler  
- Applying classification metrics to evaluate performance  
- Using ROC-AUC to understand diagnostic capability  

---

## 🔮 Future Improvements

- Integrate real-world datasets (e.g., PIMA Diabetes)
- Apply model tuning (GridSearchCV, cross-validation)
- Compare results with other models like SVM, Decision Tree, Random Forest

---

## 👤 Author

**Mahesh Babu**  
Passionate about using AI to solve real-world problems in healthcare and beyond.  

📎 [LinkedIn](https://www.linkedin.com/in/mahesh-bestha-354232303/) | 📂 [GitHub](https://github.com/BesthaMahesh)

---
