# Flight Fare Prediction

## Project Overview
This project predicts airline ticket prices using machine learning regression algorithms based on various flight details such as airline, source, destination, duration, total stops, and journey date.

## Problem Statement
Flight ticket prices vary dynamically depending on multiple factors. The objective of this project is to build a machine learning model capable of accurately predicting flight fares.

## Dataset Information
The dataset contains:
- Airline
- Date of Journey
- Source
- Destination
- Route
- Duration
- Total Stops
- Additional Information
- Price

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Outlier Treatment
5. Feature Engineering
6. Encoding Categorical Variables
7. Model Building
8. Hyperparameter Tuning
9. Cross Validation
10. Model Evaluation

## Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Best Model Performance
### Tuned Random Forest Regressor

- MAE: 610.14
- RMSE: 1155.80
- R² Score: 0.9177
- Cross-validation R²: 0.9220

## Key Insights
- Duration_minutes was the most important feature.
- Random Forest performed significantly better than Linear Regression.
- Proper feature engineering improved prediction accuracy.

## Challenges Faced
- Handling missing values
- Converting duration and date columns
- Encoding categorical variables
- Managing outliers
- Preventing overfitting

## Conclusion
The project successfully predicts airline ticket prices with high accuracy using machine learning techniques.

## Future Improvements
- Build a Streamlit web application
- Deploy the model online
- Use real-time airline datasets