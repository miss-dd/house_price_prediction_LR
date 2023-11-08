# Linear Regression Project

## Overview
This project implements a linear regression model for predicting housing prices based on various features. The project is divided into three main parts:

1. **Data Preprocessing:**
   - The raw dataset (`House_Price.csv`) is cleaned to handle missing values and outliers.
   - Features are standardized to ensure consistent scaling.
   - Categorical variables are encoded for compatibility with the linear regression model.

2. **Assessing Model Accuracy:**
   - The accuracy of the linear regression model is assessed using the Mean Squared Error (MSE) and R-squared metrics.
   - Results and insights from the evaluation are presented in the `results/evaluation_report.txt` file.

3. **Test-Train Split:**
   - The dataset is split into training and testing sets using an 80-20 ratio.
   - The rationale behind this split is to ensure a sufficient amount of data for training while retaining a sizable portion for evaluating the model's performance.

## Getting Started
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/miss-dd/house_price_prediction_LR
   
## Project Structure
data/: Contains the raw dataset (House_Price.csv) and the processed data.
scripts/: Holds the scripts for data preprocessing (preprocess.py) and model implementation (linear_regression_model.py).
results/: Stores the output, including the evaluation report (evaluation_report.txt).

## Dependencies
numpy
pandas
seaborn

## Contributing
If you would like to contribute to the project, please follow the contribution guidelines.

## License
This project is licensed under Start Tech Academy.

## Acknowledgments
The project structure was inspired by the StartTech Academy.
Special thanks to Shadrach Darku, and contributors.
