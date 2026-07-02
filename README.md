# Breast Cancer Prediction Using Machine Learning

This project applies Machine Learning techniques to predict whether a breast tumor is **Benign** or **Malignant** using medical diagnostic data. The model is built using **Logistic Regression** and trained on the Breast Cancer dataset available through the Scikit-learn library.

The project demonstrates the complete machine learning workflow, including data loading, exploration, preprocessing, model training, evaluation, and prediction on new patient data.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin Diagnostic Dataset provided by Scikit-learn.

It contains diagnostic measurements extracted from digitized images of breast mass cell nuclei. These features are used to classify tumors into:

* Malignant (Cancerous)
* Benign (Non-cancerous)

## Project Workflow

1. Load the breast cancer dataset from Scikit-learn.
2. Convert the dataset into a Pandas DataFrame.
3. Explore the data and check for missing values.
4. Analyze feature statistics and target distribution.
5. Split the dataset into training and testing sets.
6. Train a Logistic Regression model.
7. Evaluate model performance using accuracy metrics.
8. Predict tumor classification for new input samples.

## Model

The classification model used in this project is:

* Logistic Regression

The model was trained using 80% of the dataset and tested on the remaining 20%.

## Evaluation

Model performance was evaluated using:

* Accuracy Score
* Training Accuracy
* Testing Accuracy

These metrics were used to assess the model's ability to correctly classify breast tumors.

## Sample Predictions

The trained model can accept new diagnostic measurements and predict whether the tumor is:

* Malignant
* Benign

Two sample cases were tested in the notebook to demonstrate the prediction process.

## Objective

The main objective of this project is to explore how machine learning can assist in the early detection of breast cancer and support data-driven medical decision-making through accurate classification models.
