# This Project is a Homework Assignment for CS 4372.501
# Garments Worker Productivity Analysis

This project explores a dataset on garments worker productivity to build and compare two regression models:

1.  **Stochastic Gradient Descent (SGD) Regressor:** A machine learning model that iteratively optimizes its parameters.

2.  **Ordinary Least Squares (OLS) Regressor:** A statistical model that finds the best-fit line by minimizing the sum of the squared residuals.



## Prerequisites

To run this project, you need a Python environment with the following libraries. You can install them using `pip`:

```bash
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn jupyter
```

## How to Run the Code

1.  **Open the Jupyter Notebook:**
    Start a Jupyter Notebook server in your terminal from the project directory:

    ```bash
    jupyter notebook
    ```

    This will open a browser window with the Jupyter interface. Select `MainCode.ipynb` to open the notebook. If it does not auto-lauch, please control-right click the link from the terminal

2.  **Run the Cells:**
    Execute the notebook cells in order, from top to bottom.

      * **Data Loading:** The first cells load the dataset directly from a GitHub repository using `pandas.read_csv()`.

      * **Attribute Analysis:** This section provides an overview of the dataset, including data types, null values, and a summary of numerical features.

      * **Data Preprocessing:** This section cleans and transforms the data for model use. It handles null values, encodes categorical variables, and scales numerical features. A pipeline is used to ensure consistent transformations.

      * **Model Development:** This section is split into two parts for each model. The SGD Regressor section includes a grid search to find the optimal hyperparameters. The OLS Regressor section uses `statsmodels` to fit a linear model and provides a detailed summary of the results.

## Contributers
@vaipos - Vaishnavi Pasumathi
@Mariptime - Akshay Nagarajan

CS 4372.501 - Assignment 1
Anurag Nagar - Fall 2025