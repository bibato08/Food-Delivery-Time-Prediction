# Food Delivery Time Prediction Using Machine Learning

## PROJECT OVERVIEW

This project aims to predict food delivery time using machine learning regression algorithms. It analyzes different factors that influence delivery duration, including distance, weather conditions, traffic level, time of day, vehicle type, food preparation time, and courier experience.

The project implements Multiple Linear Regression and several nonlinear regression algorithms to compare their predictive performance.

## OBJECTIVES

- Analyze factors affecting food delivery time.
- Perform data cleaning and exploratory data analysis (EDA).
- Preprocess numerical and categorical features.
- Build and evaluate multiple regression models.
- Compare model performance using R² Score, MAE, and RMSE.

## DATASET FEATURES

| Feature | Description |
|---|---|
| Distance_km | Delivery distance in kilometers |
| Weather | Weather conditions |
| Traffic_Level | Traffic density |
| Time_of_Day | Delivery time period |
| Vehicle_Type | Delivery vehicle |
| Preparation_Time_min | Food preparation duration |
| Courier_Experience_yrs | Courier experience |
| Delivery_Time_min | Target variable |

## TECHNOLOGIES USED

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## MACHINE LEARNING ALGORITHMS

1. Multiple Linear Regression
2. Polynomial Regression
3. Decision Tree Regression
4. Random Forest Regression
5. Gradient Boosting Regression
6. Extra Trees Regression

## PROJECT WORKFLOW

1. Dataset collection
2. Data understanding
3. Data cleaning
4. Missing value handling
5. Exploratory Data Analysis
6. Feature selection
7. Train-test splitting
8. One-Hot Encoding
9. Model training
10. Model evaluation
11. Model comparison
12. Final conclusion

## MODEL EVALUATION

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The initial experiment achieved an approximately 0.82 R² score with Multiple Linear Regression on the held-out test set. Actual results may vary depending on the dataset version and execution environment.

## PROJECT STRUCTURE

```text
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Times.csv
├── Food_Delivery_Time_Prediction.ipynb
├── README.md
└── requirements.txt
```

## HOW TO RUN THE PROJECT

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Make sure the CSV dataset is in the same folder as the notebook.
5. Run the notebook cells sequentially.

## INSTALLATION

```bash
pip install -r requirements.txt
```

## CONCLUSION

This project demonstrates how machine learning regression algorithms can be used to estimate food delivery duration. The comparison of linear and nonlinear models helps evaluate their suitability for delivery-time prediction and demonstrates the importance of relevant features in building predictive models.
