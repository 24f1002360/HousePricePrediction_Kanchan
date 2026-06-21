# House Price Prediction

### Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze housing data, identify the factors that influence property prices, and build predictive models capable of estimating house prices based on property characteristics.

The project includes data exploration, preprocessing, visualization, model training, evaluation, and business insights.

---

## Dataset

Dataset Used: Housing Prices Dataset

Target Variable:

* Price

Features:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

---

## Project Workflow

### Task 1: Data Loading & Exploration

* Loaded dataset using Pandas
* Explored dataset structure
* Identified target and feature variables
* Checked missing values and dataset dimensions

### Task 2: Data Cleaning

* Checked and removed duplicates
* Applied One-Hot Encoding to categorical features
* Prepared final dataset for model training

### Task 3: Model Building

Models Used:

1. Linear Regression
2. Random Forest Regressor

Evaluation Metrics:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Results

| Model                   | MAE       | RMSE      | R² Score |
| ----------------------- | --------- | --------- | -------- |
| Linear Regression       | 970,043   | 1,324,507 | 0.653    |
| Random Forest Regressor | 1,013,969 | 1,398,116 | 0.613    |

### Best Model

Linear Regression achieved the best performance on this dataset with the highest R² score and lowest prediction errors.

---

## Key Findings

* Area is the most important factor influencing house prices.
* Bathrooms, air conditioning, parking availability, and number of stories also significantly affect property value.
* Houses with premium amenities generally command higher prices.
* The dataset shows a positive relationship between property size and market price.

---

## Visualizations

The repository includes:

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

All charts are available in the `charts/` directory.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Kaggle Notebook

---

## Repository Structure

```text
HousePricePrediction_GauravDalal/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

---

## Author

Kanchan 

