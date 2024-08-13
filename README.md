# LoanPrediction

**Overview**

This repository contains Python code for a loan prediction application. It utilizes KNN regression and logistic regression models for prediction, with standard scaling applied to numerical features. The application also includes a Streamlit interface for user interaction.

**Dependencies**

pandas numpy sklearn streamlit

**Data**

The dataset used for training and prediction is loan_approval_prediction.csv The columns are as follows: loan_id no_of_dependents education self_employed income_annum loan_amount loan_term cibil_score residential_assets_value commercial_assets_value luxury_assets_value bank_asset_value   loan_status

**Usage**

Data Preparation: Ensure the dataset loan_approval_dataset.csv is in the same directory as the code. Model Training: Run loanpredictionapp.ipynb to train the KNN and logistic regression models. This will create a loan_model.pkl file containing the trained models. Streamlit App: Run streamlit run streamlit_app.py to start the Streamlit application. All of this is done in the Google Colab and then uploaded

**Model Evaluation**

The code includes evaluation metrics like accuracy, precision, recall, and F1-score to assess the performance of both models this id done by classification report.

**Additional Notes**

The code assumes that necessary libraries are installed in your environment. Use pip install -r requirements.txt to install them if needed. The Streamlit app provides a user-friendly interface to input loan details and get predictions. The model is saved as a pickle file for future use. In colab the necessary libraries were needed to be installed and also the streamlit app is run through a tunnel website.
