
# **Heart Disease Prediction Using Machine Learning 🏥💖**  

This project aims to predict whether a person has heart disease based on medical attributes using **Logistic Regression**. It is built using Python and **scikit-learn** and trained on a structured dataset containing patient health indicators.  

## 📌 **Project Overview**  
Heart disease is one of the leading causes of death worldwide. **Early detection** can help in timely medical intervention. This project uses **supervised learning** to classify patients into two categories:  
✅ **0 - No Heart Disease**  
❌ **1 - Has Heart Disease**  

We train a **Logistic Regression model** using **labeled patient data** and evaluate its accuracy.  

## 📂 **Dataset Details**  
The dataset consists of multiple **medical attributes** such as:  
- **Age** → Patient's age  
- **Sex** → Male (1) / Female (0)  
- **Chest Pain Type (cp)** → Types of chest pain experienced  
- **Blood Pressure (trestbps)** → Resting blood pressure (in mm Hg)  
- **Cholesterol (chol)** → Serum cholesterol (in mg/dl)  
- **Fasting Blood Sugar (fbs)** → Blood sugar level (1 = high, 0 = normal)  
- **Resting ECG (restecg)** → Electrocardiogram results  
- **Max Heart Rate (thalach)** → Maximum heart rate achieved  
- **Exercise-Induced Angina (exang)** → Pain triggered by exercise (1 = Yes, 0 = No)  
- **ST Depression (oldpeak)** → Depression induced by exercise  
- **Slope of ST segment (slope)** → Measurement of the ST segment  
- **Number of Major Vessels (ca)** → Count of major blood vessels  
- **Thalassemia (thal)** → Blood disorder information  
- **Target (target)** → 0 = No Disease, 1 = Has Disease  

## 🛠 **Technologies Used**  
- **Python**  
- **Pandas & NumPy** (for data handling)  
- **Matplotlib & Seaborn** (for data visualization)  
- **Scikit-learn** (for machine learning)  

4. Use **Colab/Jupyter Notebook** for interactive execution.

## 📊 **Model Training & Evaluation**  
- **Splitting Data:** 80% Training, 20% Testing  
- **Model Used:** Logistic Regression  
- **Performance Metrics:**  
  - Training Accuracy ✅  
  - Testing Accuracy ✅  
  - Predictions on new data ✅  

## 🏥 **Making Predictions**  
To test a new patient's data, input the values like:  
```python
input_data = (62,0,0,140,268,0,0,160,0,3.6,0,2,2)
```
📌 **Output Example:**  
- **"The Person has Heart Disease"** 🛑  
- **"The Person does not have a Heart Disease"** ✅  

## 🎯 **Future Improvements**  
- Try different machine learning models (e.g., Random Forest, SVM).  
- Improve accuracy with hyperparameter tuning.  
- Deploy as a web application using Flask or Django.  



**💡 Contribute & ⭐ Star this Repo if you found it helpful!** 🚀  

