#  Heart Disease Prediction using Machine Learning

##  Project Overview

This project aims to predict the presence of heart disease in a patient based on medical attributes using machine learning algorithms. This is a small educational dataset comparison, not a diagnostic tool or a clinically validated model.

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
3. Exploratory Data Analysis (EDA)
4. Train-Test Split (80:20)
5. Feature scaling using StandardScaler fitted on training data only
6. Model Training
7. Model Evaluation

---

## Model Performance

Test accuracy on the 80:20 split (`random_state=42`, features scaled with StandardScaler fitted on the training set only):

| Model | Test Accuracy |
|---|---|
| K-Nearest Neighbors | 90.2% |
| Support Vector Machine | 86.9% |
| Logistic Regression | 85.2% |
| Random Forest | 83.6% |

The notebook runs end to end (`model.ipynb`): preprocessing, train/test split, scaling, training and comparison, with saved outputs.

### Limits

The notebook reports accuracy only on 61 test records from one fixed split. It does not yet report cross-validation, sensitivity/specificity, calibration or external validation. Results from this small split should not be treated as clinical evidence.

---

##  Key Insights

* KNN achieved the highest test accuracy (90.2%) on this dataset
* StandardScaler is fitted only on training data, then applied to the test data
* Logistic Regression is a solid, interpretable baseline at 85.2%


---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yuvasree023/Heart_disease_prediction.git
```

2. Navigate to the project folder

```
cd Heart_disease_prediction
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Open `model.ipynb` in Jupyter and run all cells from the repository root. A clean run is saved in the notebook.

---

##  Future Improvements

* Hyperparameter tuning
* Deploy as a web app (Streamlit)
* Add more real-world medical data
* Improve model interpretability

---

##  Conclusion

This project demonstrates how machine learning can be applied to healthcare for predicting heart disease. The results are an educational comparison on a small dataset, not evidence of clinical reliability.

---

## Contact

Feel free to connect for collaboration or queries!
