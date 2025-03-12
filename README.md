# Credit Risk Modeling App

This app allows users to input borrower details and predict the likelihood of **loan default**. The model is designed to assist financial institutions in assessing **credit risk** and making informed lending decisions.

### Model Details
1. **Data Processing & Feature Selection:**
   - Cleaned and preprocessed the dataset.
   - Used **Variance Inflation Factor (VIF)** to remove multicollinearity in numerical features.
   - Applied **Information Value (IV)** for categorical feature selection.
   
2. **Model Training & Optimization:**
   - Used **XGBoost** for predictive modeling.
   - Addressed **class imbalance** using appropriate resampling techniques.
   - Tuned hyperparameters with **Optuna** to enhance performance.

3. **Model Performance:**
   - Achieved **90%+ recall** to effectively detect potential defaulters.
   - Maintained an **error rate of less than 5%**.
   - Deployed an **interactive UI with Streamlit** for real-time risk assessment.

### Set Up

1. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
2. Run the Streamlit app:
   ```commandline
   streamlit run app.py
