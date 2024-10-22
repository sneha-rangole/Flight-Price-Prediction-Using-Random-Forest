# Flight Price Prediction Using Random Forest

## Project Overview

This project focuses on developing a machine learning model using **Random Forest Regression** to predict flight prices based on historical data. The model helps consumers make informed decisions when booking flights, and can also be used by airlines and travel agencies to optimize their pricing strategies.

### Key Features:
- **Exploratory Data Analysis (EDA)**: Understanding the data distribution, visualizing trends, and identifying important features.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and normalizing numerical data.
- **Feature Engineering**: Identifying key features that affect flight pricing.
- **Model Implementation**: Using Random Forest to predict flight prices with an R² score of 0.812.
- **Model Evaluation**: Evaluating the model using metrics like MAE, MSE, and RMSE.

## Dataset

The dataset used for this project includes the following key features:
- **Airline**: Airline carrier name
- **Source & Destination Airports**: Departure and arrival airports
- **Departure Date**: Date and time of the flight
- **Flight Duration**: Total duration of the flight
- **Layovers**: Number of layovers
- **Price**: Flight ticket price (target variable)

## Methodology

1. **Data Cleaning**: Addressed missing values and outliers, and prepared the dataset for modeling.
2. **Exploratory Data Analysis (EDA)**: Used visualizations (histograms, box plots, scatter plots) to analyze data distribution and feature relationships.
3. **Feature Engineering**: Identified relevant features using correlation heatmaps and feature importance analysis.
4. **Modeling**: Implemented a Random Forest Regression model.
5. **Model Tuning**: Used hyperparameter tuning (RandomizedSearchCV) to optimize the model.
6. **Model Evaluation**: Tested the model using metrics like MAE, MSE, RMSE, and R² Score.

## Results

The Random Forest model achieved the following results:
- **Mean Absolute Error (MAE)**: 1165.61
- **Mean Squared Error (MSE)**: 4,062,650.69
- **Root Mean Squared Error (RMSE)**: 2015.60
- **R² Score**: 0.812

## Installation

To run this project locally:

1. Clone the repository.
    ```bash
    git clone https://github.com/sneha-rangole/flight-price-prediction.git
    ```
2. Navigate to the project directory.
    ```bash
    cd flight-price-prediction
    ```
3. Install the necessary packages.
    ```bash
    pip install -r requirements.txt
    ```
4. Prepare the dataset and ensure it is placed in the correct directory.


## Conclusion

The project successfully implemented a Random Forest regression model to predict flight prices with a reasonably high accuracy. The model is capable of understanding complex relationships between various features, making it a robust tool for airline ticket price prediction.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

