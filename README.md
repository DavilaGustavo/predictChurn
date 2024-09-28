<p align="center">
  <img src="https://github.com/user-attachments/assets/a63f5c31-1275-4d4f-a6dd-8fd2586179f4">
</p>

# Customer Churn Prediction (Random Forest)

This repository contains a project aimed at predicting customer churn using a Random Forest model. The dataset used for this project can be found in the [WA_Fn-UseC_-Telco-Customer-Churn.csv](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) file, which includes various features related to customer demographics, services, and account information. The code is implemented in Python and utilizes popular machine learning libraries to create a model for classifying whether a customer will churn or not.

## Implemented Features

1. ### Data Preprocessing
   - Loading the customer churn dataset and preparing the data, including handling missing values and converting categorical variables into numeric formats using label encoding.

2. ### Model Training
   - Configuration and training of a Random Forest model to classify customers based on their likelihood to churn. The model is tuned using some hyperparameters to optimize performance.

3. ### Model Evaluation
   - Evaluation of the model using metrics like accuracy, confusion matrix, and classification report. Visualization of the model's performance through ROC curves for both training and testing datasets.

4. ### SHAP Values for Interpretability
   - Using SHAP (SHapley Additive exPlanations) to analyze feature importance and understand the model's predictions, with the generation of summary plots for better interpretability.

## Tools Used
- **Python**: Main programming language.
- **Python Libraries**: scikit-learn, pandas, NumPy, Matplotlib, SHAP.
- **Development Environment**: Any Python IDE such as Jupyter Lab or Visual Studio Code.

## Main Project Structure

- **`predictChurn.ipynb`**: Main script to execute the training and evaluation of the Random Forest model.

## How to Use

1. **Clone the repository**:
    - git clone <rep URL>

2. **Install the required dependencies**:
    - pip install scikit-learn pandas numpy matplotlib shap

3. **Ensure the dataset is in the src directory**:
    - WA_Fn-UseC_-Telco-Customer-Churn.csv

4. **Run the main script**:
    - Run Jupyter Lab or other IDE
    - Open and run predictChurn.ipynb
        - The script will load the dataset, train the model, and evaluate its performance, generating the ROC and SHAP plots.

5. **Changes**:
    - Feel free to modify the code to adjust model parameters or experiment with different datasets.

## Contributions

Contributions are welcome! Feel free to submit pull requests with improvements, bug fixes, or new features. For discussions and suggestions, please open an issue.