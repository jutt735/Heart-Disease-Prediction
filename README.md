# Task 3: Heart Disease Prediction

## 📌 Objective
The objective of this task is to build a **machine learning model** that predicts the risk of death in heart failure patients based on clinical features.  
This project demonstrates a complete **classification pipeline** including data loading, preprocessing, model training, and evaluation.

---

## 📊 Dataset Description
The dataset is loaded **directly from Hugging Face** using the `datasets` library.

**Dataset Name:** `mstz/heart_failure`  
**Source:** Hugging Face Datasets

### Features:
- `age`: Age of the patient
- `has_anaemia`: Whether the patient has anaemia
- `creatinine_phosphokinase_concentration_in_blood`: CPK enzyme level
- `has_diabetes`: Whether the patient has diabetes
- `heart_ejection_fraction`: Percentage of blood leaving the heart at each contraction
- `has_high_blood_pressure`: Whether the patient has hypertension
- `platelets_concentration_in_blood`: Platelet count
- `serum_creatinine_concentration_in_blood`: Level of creatinine in blood
- `serum_sodium_concentration_in_blood`: Sodium level in blood
- `is_male`: Gender indicator
- `is_smoker`: Smoking status
- `days_in_study`: Follow-up duration in days

### Target Variable:
- `is_dead`
  - `1` → Patient died during follow-up  
  - `0` → Patient survived

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Hugging Face `datasets`

---

## 🔄 Workflow
1. Load dataset directly from Hugging Face
2. Explore dataset structure and columns
3. Split data into features and target
4. Perform train-test split
5. Train a Logistic Regression model
6. Evaluate model performance
7. Visualize results using confusion matrix and ROC curve

---

## 🤖 Machine Learning Model
- **Model Used:** Logistic Regression
- **Reason:** Suitable for binary classification problems and easy to interpret
- **Max Iterations:** 1000

---

## 📈 Model Evaluation
The model performance is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **ROC Curve**

These metrics help assess how well the model distinguishes between patients who survived and those who did not.

---

## 📊 Visualizations
- Confusion Matrix heatmap
- ROC Curve showing model discrimination capability

All plots are generated using Matplotlib and Seaborn.

---

## ✅ Results
The Logistic Regression model achieves a reasonable accuracy in predicting heart failure outcomes based on clinical data.  
The confusion matrix and ROC curve indicate that the model performs well in distinguishing between the two classes.

---

## 🎯 Conclusion
This project demonstrates how machine learning can be applied to healthcare data to predict patient outcomes.  
It highlights the importance of clinical features in assessing heart failure risk and showcases a complete ML pipeline suitable for real-world applications.

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
