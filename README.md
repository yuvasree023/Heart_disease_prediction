#  Heart Disease Prediction using Machine Learning

##  Project Overview

This project aims to predict the presence of heart disease in a patient based on medical attributes using machine learning algorithms. Early prediction can help in timely diagnosis and treatment.

---

##  Dataset Information

* Total records: **303**
* Features: **13 input features + 1 target**
* Target:

  * `0` → No Heart Disease
  * `1` → Heart Disease

###  Features include:

* Age
* Sex
* Chest Pain Type (`cp`)
* Resting Blood Pressure (`trestbps`)
* Cholesterol (`chol`)
* Fasting Blood Sugar (`fbs`)
* Resting ECG (`restecg`)
* Max Heart Rate (`thalach`)
* Exercise Induced Angina (`exang`)
* Oldpeak
* Slope
* CA
* Thal

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

##  Machine Learning Models

The following models were implemented and compared:

* Logistic Regression
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

---

##  Project Workflow

1. Data Collection & Loading
2. Data Preprocessing

   * Handling missing values
   * Feature scaling using StandardScaler
3. Exploratory Data Analysis (EDA)
4. Train-Test Split (80:20)
5. Model Training
6. Model Evaluation

---

## Model Performance

* Logistic Regression: ~88% accuracy
* Random Forest: High performance (~85–90%)
* KNN & SVM: Compared for evaluation

### Evaluation Metrics:

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score

---

##  Key Insights

* Feature scaling significantly improved model performance
* Logistic Regression performed well as a baseline model
* Random Forest provided strong overall accuracy


---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/heart-disease-prediction.git
```

2. Navigate to the project folder

```
cd heart-disease-prediction
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run the notebook or script

---

##  Future Improvements

* Hyperparameter tuning
* Deploy as a web app (Streamlit)
* Add more real-world medical data
* Improve model interpretability

---

##  Conclusion

This project demonstrates how machine learning can be applied to healthcare for predicting heart disease. With proper preprocessing and model selection, reliable predictions can be achieved.

---

## Contact

Feel free to connect for collaboration or queries!
