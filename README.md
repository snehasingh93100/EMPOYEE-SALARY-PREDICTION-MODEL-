# 🧠 Income Prediction Using Machine Learning

Predict whether an individual's income exceeds $50K/year based on census data using various ML algorithms. This project explores different models and selects the best-performing one — Gradient Boosting — for accurate income classification.

---

## 📌 Problem Statement

To build a machine learning model that predicts whether a person earns more than 50K annually based on attributes like age, education, occupation, work hours, and more.

---

## 📊 Dataset

- **Source**: UCI Adult Income Dataset
- **Format**: CSV (`adult.csv`)
- **Features**: Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Capital Gain, Hours per Week, etc.

---

## ⚙️ Technologies & Libraries Used

- **Python 3.8+**
- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – ML algorithms and preprocessing  
- `pickle` – Saving the trained model  

---

## 🧪 ML Algorithms Compared

| Algorithm            | Accuracy |
|---------------------|----------|
| Logistic Regression | ~81%     |
| K-Nearest Neighbors | ~78%     |
| SVM                 | ~82%     |
| Random Forest       | ~84%     |
| **Gradient Boosting** | **~86% ✅** |

✅ **Gradient Boosting** was selected as the final model.

---

## 🚀 Project Workflow

1. **Import Dataset**
2. **Preprocess Data**
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features
3. **Model Training**
   - Train multiple algorithms
   - Compare using accuracy
4. **Model Evaluation**
   - Select the best model (Gradient Boosting)
5. **Model Saving**
   - Save model using `pickle`
6. **(Optional) Deployment**
   - Integrate with web app using Flask or Streamlit

---

## 📁 Folder Structure

