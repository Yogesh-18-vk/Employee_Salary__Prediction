# Employee_Salary__Prediction
# ML Workflow using Google Colab & Streamlit

This repository contains two Google Colab notebooks that demonstrate a complete machine learning workflow—from data preprocessing to deploying a Streamlit web application.


## Contents

###  Notebook 1: Employee_Salary_prediction_1.ipynb

This notebook includes:

- Data Preprocessing
  - Handling missing values
  - Encoding categorical variables
- Outlier Detection and Removal
  - Techniques like Z-score or IQR
- Model Comparison
  - Train multiple machine learning models
  - Visual comparison using a bar graph
- Save Trained Model
  - Export best model using `joblib` or `pickle`

---

### Notebook 2: Employee_Salary_prediction_2.ipynb

This notebook includes:

- Model Exporting
  - Load saved model from Notebook 1
- Create `app.py` using Streamlit
  - Accept user input
  - Show model prediction
- Run Web Application
  - Run locally using `streamlit run app.py`
  - Generate URL if hosted (e.g., via Streamlit Share)


