# Support Vector Machine (SVM) Credit Card Prediction

This project demonstrates the application of Support Vector Machines (SVM) for predicting credit card holders based on a provided dataset. The project explores different SVM kernels to assess their performance.

## Dataset

The project utilizes the `UniversalBank.csv` dataset. This dataset contains information about customers of a universal bank, including demographics, account information, and their response to a personal loan campaign. The target variable for this project is `CreditCard`, which indicates whether a customer holds a credit card issued by the bank.

## Project Structure

The project involves the following steps:

1.  **Data Loading and Exploration:** Loading the dataset and performing initial data exploration, including visualizing the correlation between features.
2.  **Data Preprocessing:**
    *   Dropping irrelevant columns (`ID` and `ZIP Code`).
    *   Scaling the features using `StandardScaler` to ensure all features contribute equally to the model.
3.  **Data Splitting:** Splitting the data into training and testing sets.
4.  **SVM Model Training and Evaluation:**
    *   Training SVM models with different kernels:
        *   Default (rbf)
        *   Linear
        *   Radial Basis Function (RBF)
        *   Polynomial
        *   Sigmoid
    *   Evaluating the performance of each model using:
        *   Accuracy Score
        *   Confusion Matrix
        *   Classification Report

## Requirements

To run this project, you will need the following libraries:

*   `numpy`
*   `pandas`
*   `matplotlib`
*   `seaborn`
*   `sklearn`


## How to Run

1.  Clone the repository to your local machine.
2.  Ensure you have the required libraries installed.
3.  Place the `UniversalBank.csv` file in the same directory as the notebook.
4.  Open the notebook in a Jupyter environment (like Google Colab or Jupyter Notebook).
5.  Run the cells sequentially to execute the project steps.

## Results

- Model accuracy : 0.749
- Model accuracy with linear kernel : 0.747
- Model accuracy with rbf kernel : 0.749
- Model accuracy with polynomial kernel : 0.749
- Model accuracy with sigmoid kernel : 0.629
