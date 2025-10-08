# Linear Regression Analysis

## Project Overview

This project demonstrates the application of linear regression on multiple datasets to model and predict outcomes. Five regression tasks are performed, including both simple and multiple linear regression, with predictions and visualizations highlighting model performance.

## Datasets

Study Hours vs Exam Score – Records study hours and corresponding exam scores.

House Size vs Price – Contains house sizes in square meters and their prices.

Salary vs Experience – Contains years of experience and corresponding salaries.

House Price with Size and Bedrooms – Contains house sizes, number of bedrooms, and prices.

Advertising Spend vs Sales – Contains spending on TV, radio, and social media along with resulting sales.

## Regression Tasks and Results

## 1. Study Hours → Exam Score

Objective: Predict exam score based on study hours.

Results: The model captures the positive correlation between study hours and score.

Prediction Example: Predicted score for 9 hours of study.

Visualization: Scatter plot shows actual scores, regression line, and highlighted prediction.

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/59d55fc5-0aa2-4b31-8f02-32c40d0320d7" />

## 2. House Size → Price

Objective: Predict house price from its size.

Results: Linear relationship shows price increases with house size.

Prediction Example: Price prediction for a 120 m² house.

Visualization: Scatter plot with regression line and prediction point.

<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/7f06053b-e9f4-4723-b4b7-c004dee3b073" />

## 3. Salary vs Experience

Objective: Predict salary based on years of experience.

Results: Salary generally increases with experience; model fits the trend.

Prediction Example: Salary for 7 years of experience.

Visualization: Scatter plot shows actual salaries, regression line, and highlighted prediction.

<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/20d3ec35-bb69-4f92-ae9b-7bf17bb3a7fc" />

## 4. House Price ~ Size + Bedrooms

Objective: Predict house price using size and number of bedrooms.

Results: Multiple regression accounts for combined effects of both features.

Prediction Example: Price for a house of 85 m² with 3 bedrooms.

Visualization: Predicted vs actual plot with a highlighted predicted house and perfect prediction line.

<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/76f7f04e-1a6c-43ed-a765-791e764c312f" />

## 5. Advertising Spend → Sales

Objective: Predict sales based on advertising spend across TV, radio, and social media.

Results: Multi-feature regression shows contributions of each medium to sales.

Prediction Example: Sales prediction for specific spend values.

Visualization: Predicted vs actual plot with highlighted predicted sales.

<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/36cd3bf7-96eb-4083-9010-ba31e4d19ab5" />

## Key Insights

Simple Linear Regression: Effective for single-feature prediction. Positive correlations are easily visualized.

Multiple Linear Regression: Captures combined effects of multiple features. Coefficients indicate feature impact.

Predictions: Highlighted in plots to show practical use of models.

R² Score: Indicates how well the models explain variation in the target variable.

## Visualization Summary

Scatter plots show actual vs predicted values for all datasets.

Regression lines highlight trends.

Predicted points are emphasized to show the application of the models.

## Applications

Education: Estimate student performance from study hours.

Real Estate: Predict house prices from size and features.

HR Analytics: Forecast salary based on experience.

Marketing: Assess impact of advertising spend on sales.

## Conclusion

This project demonstrates the complete workflow of regression modeling, from data loading to prediction and visualization. The approach shows how regression can be applied to real-world datasets, providing practical insights and accurate predictions.

## Libraries Used

pandas – For data handling

scikit-learn – For Linear Regression and R² calculation

matplotlib – For plotting
