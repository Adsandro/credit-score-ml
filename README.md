
# Credit Score Prediction using Machine Learning

This repository contains a Python project for predicting credit scores using machine learning techniques. The goal of this project is to develop a model that can accurately predict a customer's credit score based on various features and attributes. The project involves several stages, including data preprocessing, model training, testing, and real-world prediction.

## Project Overview

The project is structured into the following stages:

1.  **Understanding Project Needs**: In this stage, the project's requirements and objectives are defined, and the challenges faced by the company are outlined.
    
2.  **Loading the Dataset**: The initial dataset containing customer information is loaded into the project. The dataset includes information about customers' professions, credit mix, and payment behavior.
    
3.  **Data Preprocessing**: To prepare the dataset for machine learning, certain columns containing categorical data are encoded using the LabelEncoder to convert them into numerical format.
    
4.  **Data Splitting**: The dataset is split into training and testing subsets. The target variable, `score_credito`, is separated from the features. Columns like `id_cliente` and `score_credito` are removed from the feature set.
    
5.  **Model Training**: Two machine learning models are trained on the training data: a RandomForestClassifier and a KNeighborsClassifier.
    
6.  **Accuracy Testing**: The accuracy of the trained models is tested using the testing data. The accuracy score is a crucial metric for selecting the best-performing model.
    
7.  **Real-world Application**: The trained RandomForestClassifier model is used to make predictions on new customer data, provided in the `novos_clientes.csv` file. The model predicts the credit scores of these new customers.
    

## How to Use

1.  Clone the repository:
    
    bashCopy code
    
    `git clone https://github.com/your-username/credit-score-prediction.git
    cd credit-score-prediction` 
    
2.  Install the required packages. It's recommended to use a virtual environment:
    
    bashCopy code
    
    `python3 -m venv venv
    source venv/bin/activate   # On Windows, use: venv\Scripts\activate
    pip install -r requirements.txt` 
    
3.  Download the necessary dataset files (`clientes.csv` and `novos_clientes.csv`) and place them in the project directory.
    
4.  Open and run the Jupyter Notebook `credit_score_prediction.ipynb` to follow along with the project's stages and see the code execution.
    
5.  Once the notebook is executed, you can observe the accuracy of the trained models and the predictions made on new customer data.
    

## Dependencies

The project utilizes the following libraries:

-   Pandas: For data manipulation and preprocessing.
-   Scikit-learn: For machine learning model creation and evaluation.

## Conclusion

This project demonstrates the process of creating a credit score prediction model using machine learning techniques. By following the stages outlined in the notebook, you can gain insights into how to preprocess data, train models, and make predictions. Additionally, you can explore further enhancements such as hyperparameter tuning and feature engineering to improve model performance.