# Phone Price Prediction

This is a machine learning project where the goal is to predict how expensive a mobile phone is based on its features. The dataset contains details like RAM, internal memory, camera specs, battery capacity, and other hardware info.

## Objective

To build a classification model that predicts the price range of a phone:
- 0 = Low cost
- 1 = Medium cost
- 2 = High cost
- 3 = Very high cost

## About the Dataset

- 2000 rows, 20 features
- No missing values
- All features are numeric or binary (already preprocessed)
- Target: `price_range`

## What I Did

- Explored the data and checked for balance and missing values
- Scaled the features using StandardScaler
- Trained three models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- Evaluated the models using accuracy, confusion matrix, and classification report

## Results

Random Forest gave the best performance overall. Some of the most important features for predicting price were:
- RAM
- Battery power
- Pixel resolution (height × width)
- Internal memory

## Files

- `phone_price_prediction.ipynb` – notebook with code and results
- `phoneprice.csv` – dataset 

## How to Run

Open the notebook in Google Colab or Jupyter, upload the CSV file if needed, and run all cells.

