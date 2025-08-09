### Heart Disease Prediction Project 

This README file provides an overview of the Jupyter notebook [Heart_Disease_Prediction.ipynb](https://github.com/Anujjadaun97/HEART-DISEASE-PREDICTION/blob/main/Heart_Disease_Prediction.ipynb), which focuses on building a machine learning model to predict heart disease.

---

### Project Overview

This project uses a dataset containing clinical parameters to predict whether a patient has heart disease. The notebook follows a standard machine learning workflow, including data collection, preprocessing, model training, and prediction. The primary goal is to develop a predictive model that can accurately classify patients based on their health attributes.

---

### Key Sections of the Notebook

1.  **Importing Libraries**: The notebook begins by importing essential libraries for data manipulation (`numpy`, `pandas`) and machine learning (`sklearn`). The `sklearn` libraries imported are `train_test_split`, `LogisticRegression`, and `accuracy_score`.
2.  **Data Collection and Processing**: The dataset, named [heart.csv](https://github.com/Anujjadaun97/HEART-DISEASE-PREDICTION/blob/main/heart.csv), is loaded into a Pandas DataFrame. The notebook checks the data's shape, which is 303 rows and 14 columns, and provides a summary of the data types and non-null counts, confirming there are no missing values.
3.  **Model Training**: The notebook utilizes a **Logistic Regression** model for classification.
4.  **Prediction**: The trained model is then used to make predictions on new data, demonstrating its practical application.

---

### How to Run the Notebook

To run this notebook, you will need to have the following libraries installed:
* `numpy`
* `pandas`
* `scikit-learn`

The notebook also requires a [heart.csv](https://github.com/Anujjadaun97/HEART-DISEASE-PREDICTION/blob/main/heart.csv) file, which is loaded from the `/content/heart.csv` path. You will need to ensure this file is present in the specified location or update the file path in the notebook.
