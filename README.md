#   California Housing Prices Prediction

## Overview

This project aims to predict housing prices in California using datasets from Kaggle. It leverages two powerful machine learning models, Random Forest and Linear Regression, to perform the predictions. The project includes comprehensive steps such as data preprocessing, model training, evaluation, and visualization of results through various charts and graphs.

## Dataset

The dataset used in this project is the California Housing Prices dataset, sourced from Kaggle. The dataset contains various features, including:
- Median income
- House age
- Average number of rooms
- Average number of bedrooms
- Population
- Average occupancy
- Latitude
- Longitude

These features are used to predict the median house value in different districts across California.

## Key Features

### Data Preprocessing
- **Handling Missing Values:** Ensures that the dataset is complete by dealing with any missing data.
- **Feature Scaling:** Normalizes the data to ensure all features contribute equally to the model.
- **Train-Test Split:** Splits the data into training and testing sets to evaluate the model's performance effectively.

### Model Training
- **Random Forest Regressor:** An ensemble learning method that operates by constructing multiple decision trees and outputting the average prediction of the individual trees.
- **Linear Regression:** A linear approach to modeling the relationship between a dependent variable and one or more independent variables.

### Model Evaluation
- **Mean Squared Error (MSE):** Measures the average of the squares of the errors, providing a sense of how close the predicted values are to the actual values.
- **R-squared (R²):** Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **Cross-validation:** Ensures the model's robustness by validating it on different subsets of the data.

### Visualization
- **Feature Importance:** Visualizes which features have the most impact on the predictions made by the Random Forest model.
- **Prediction vs Actual Values:** Compares the predicted housing prices to the actual prices to visualize the model's accuracy.

## Usage

1. **Data Preprocessing:** Prepare the dataset by cleaning and normalizing the data.
2. **Model Training:** Train the Random Forest and Linear Regression models using the training dataset.
3. **Model Evaluation:** Evaluate the models using metrics such as MSE and R², and visualize the results.
4. **Visualization:** Generate charts to understand feature importance and compare predicted values against actual values.

## Results

The project demonstrates the application of machine learning models to predict housing prices in California. By comparing the performance of Random Forest and Linear Regression models, the project provides insights into the strengths and weaknesses of each approach. Visualizations help to understand the significance of different features and the accuracy of the predictions.

### Feature Importance
Feature importance charts show which features contribute the most to the Random Forest model's predictions.

### Prediction vs Actual Values
Charts comparing predicted and actual values highlight the model's accuracy and potential areas for improvement.

## Conclusion

This project successfully applies machine learning techniques to predict housing prices in California. By using Random Forest and Linear Regression models, it demonstrates the effectiveness of these methods in real-world data scenarios. The visualizations and evaluation metrics provide a clear understanding of the model's performance and the importance of different features.

## Acknowledgements

- [Kaggle](https://www.kaggle.com/) for providing the dataset.
- [Scikit-learn](https://scikit-learn.org/) for the machine learning library.
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for visualizhttps://www.youtube.com/shorts/LwdOKvKh8SU
