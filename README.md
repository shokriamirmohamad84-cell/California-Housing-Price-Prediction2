# California Housing Price Prediction

## 1. Project Overview

This project uses Machine Learning to predict California housing prices based on different housing features.

The main goal is to build a Non-Linear Regression model using Random Forest.

## 2. Dataset

Dataset: California Housing Dataset

Source: Scikit-learn

Number of Samples: 20,640

Number of Features: 8

## 3. Features

The dataset contains the following features:

- MedInc: Median Income
- HouseAge: Median House Age
- AveRooms: Average Rooms
- AveBedrms: Average Bedrooms
- Population: Population
- AveOccup: Average Occupancy
- Latitude: Latitude
- Longitude: Longitude

Target:
- MedHouseVal: Median House Value

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 5. Machine Learning Algorithm

Random Forest Regression

Model Parameters:
- n_estimators = 100
- max_depth = 15
- random_state = 42

## 6. Model Training

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

The Random Forest model was trained using the training dataset.

## 7. Model Evaluation

Results:

- R2 Score: 0.8004
- MSE: 0.2615
- RMSE: 0.5114

The model achieved an R2 score of approximately 80%.

## 8. Prediction

The trained model can predict house prices using eight input features.

## 9. Conclusion

This project demonstrates how Random Forest Regression can be used to predict housing prices using Machine Learning.

---

Created with Python and Scikit-learn.
