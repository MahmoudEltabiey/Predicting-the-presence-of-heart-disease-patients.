# Heart Disease Prediction using Machine Learning

## Problem
Heart disease is one of the leading causes of death worldwide. Early detection can help doctors provide better treatment and reduce risk.  
This project builds a **machine learning model to predict the presence of heart disease in a patient based on medical attributes**.

---

## Approach
The project follows a standard machine learning pipeline:

1. **Data Preprocessing**
   - Handle missing values using `SimpleImputer`
   - Encode categorical variables using **One-Hot Encoding**
   - Prepare feature matrix and target variable

2. **Data Splitting**
   - Split the dataset into **training (80%) and testing (20%)** sets using `train_test_split`

3. **Model Training**
   - Train a **Random Forest Classifier** to learn patterns in the medical data.

4. **Model Evaluation**
   - Evaluate performance using:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
     - Confusion Matrix
   - Apply **10-fold cross-validation** to check model stability.

---

## Model
The main model used in this project:

- **Random Forest Classifier**

The model was further improved using:
- Increased number of trees (`n_estimators=200`)
- Parallel processing (`n_jobs=-1`)

---

## Results
The optimized Random Forest model successfully predicts the presence of heart disease with high accuracy = 0.90.

Evaluation metrics used:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Cross-validation score**

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Author
**Mahmoud Eltabiey**
