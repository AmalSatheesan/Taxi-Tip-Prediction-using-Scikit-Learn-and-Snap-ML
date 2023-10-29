# Taxi Tip Prediction using Scikit-Learn and Snap ML

## Overview
This project focuses on comparing the training speedup between Scikit-Learn and Snap ML for building a Decision Tree Regressor model. It also includes running inference using both models and evaluating the Mean Squared Error (MSE) on the test dataset to assess their predictive performance.

## Dataset
The dataset used in this project includes information about taxi trips and tip amounts. The dataset was collected and provided by the NYC Taxi and Limousine Commission (TLC). You can access the dataset at [this link](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page).

## Project Contents
- Jupyter Notebook: [taxi_tip_prediction.ipynb](taxi_tip_prediction.ipynb)
  - Basic data preprocessing using Scikit-Learn
  - Building a Decision Tree Regressor model using Scikit-Learn
  - Building a Decision Tree Regressor model using Snap ML
  - Comparing training speedup between Scikit-Learn and Snap ML
  - Running inference using both models
  - Evaluating Mean Squared Error (MSE) on the test dataset


## How to Run

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>

2. Navigate to the project directory:
   ```bash
   cd taxi-tip-prediction

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook taxi_tip_prediction.ipynb

## Project Steps

This project involves several key steps:

1. **Data Preparation:**
   - Acquire the taxi trip dataset from the NYC Taxi and Limousine Commission (TLC).
   - Perform basic data preprocessing using Scikit-Learn, including data cleaning and feature engineering.

2. **Dataset Split:**
   - Divide the pre-processed dataset into a training set and a test set using Scikit-Learn's `train_test_split` function.

3. **Scikit-Learn Decision Tree Model:**
   - Build a Decision Tree Regressor model using Scikit-Learn.
   - Set the model parameters and train it on the training data.

4. **Snap ML Decision Tree Model:**
   - Build a Decision Tree Regressor model using Snap ML, which offers multi-threaded CPU/GPU training.
   - Set the model parameters and train it on the training data.

5. **Model Comparison:**
   - Compare the training speedup between Scikit-Learn and Snap ML.
   - Run inference using both models on the test dataset.

6. **Model Evaluation:**
   - Evaluate the Mean Squared Error (MSE) on the test dataset for both Scikit-Learn and Snap ML models.

7. **Repository Setup:**
   - Clone this repository to your local machine.
   - Install the required libraries from the `requirements.txt` file.
   - Open and run the Jupyter Notebook to explore and run the project.



## Acknowledgments
- [Scikit-Learn](https://scikit-learn.org/)
- [Snap ML](https://www.zurich.ibm.com/snapml/)

## Author
- Amal Satheesan
- amalsatheesan2000@gmail.com
- [AmalSatheesan](https://github.com/AmalSatheesan)


