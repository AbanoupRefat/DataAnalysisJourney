# Linear Regression Project on E-commerce Customers Dataset

## Project Overview
This project applies linear regression to an E-commerce Customers dataset to predict the yearly amount spent by customers based on various features like average session length, time on app, time on the website, and length of membership.

## Objective
The primary goal of this project is to build a linear regression model that accurately predicts the `Yearly Amount Spent` by customers. The project also aims to explore the relationships between different features and understand how they contribute to the target variable.

## Dataset
- **Source**: The dataset contains information on customers of an e-commerce platform.
- **Features**:
  - `Avg. Session Length`: Average session length with a stylist.
  - `Time on App`: Time spent on the mobile app.
  - `Time on Website`: Time spent on the website.
  - `Length of Membership`: Duration of membership.
  - `Yearly Amount Spent` (Target): The amount spent by a customer annually.

## Project Structure
The project is organized into the following sections:
1. **Introduction**: Overview of the dataset and the objective of the project.
2. **Data Importing and Preparation**: Loading the dataset and initial data inspection.
3. **Exploratory Data Analysis (EDA)**: Detailed exploration and visualization of the data to understand relationships and patterns.
4. **Data Preprocessing**: Scaling features and splitting the data into training and test sets.
5. **Model Training**: Building and training a linear regression model.
6. **Model Evaluation**: Assessing model performance using metrics like Mean Squared Error (MSE) and R-squared, along with visualizing residuals and predictions.
7. **Conclusions and Recommendations**: Summary of findings, model performance, and suggestions for future improvements.

## Key Findings
- **Feature Importance**: Length of Membership and Average Session Length were found to be the most significant predictors of Yearly Amount Spent.
- **Model Performance**: The linear regression model performed well, with a low Mean Squared Error and a high R-squared value, indicating a good fit.
- **Residual Analysis**: Residuals showed no significant patterns, suggesting that the model assumptions hold true.

## How to Run the Project
1. **Requirements**:
   - Python 3.x
   - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
2. **Steps**:
   - Clone the repository: `git clone <repository-url>`
   - Install the required libraries: `pip install -r requirements.txt`
   - Run the Jupyter notebook: `jupyter notebook linear_regression_project.ipynb`

## Future Work
- **Hyperparameter Tuning**: Explore Ridge and Lasso regression for better performance.
- **Model Comparison**: Compare linear regression with other models like decision trees or random forests.
- **Cross-Validation**: Implement cross-validation to ensure model robustness.

## Contributors
- **Abanoub Refat** - Data Analyst, Python Developer

## License
This project is licensed under the MIT License - see the LICENSE file for details.
