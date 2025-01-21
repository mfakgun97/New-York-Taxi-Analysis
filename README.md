# New York Taxi Analysis

This project aims to predict the fare amount passengers spend on yellow cab rides in specific regions of New York City, using temporal factors such as the hour, day, and month of the ride.

We implemented several models for fare prediction, including Decision Trees, Random Forest, and Gradient Boosting. To evaluate model performance, we used metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² (coefficient of determination). Random Forest was identified as the most effective model based on these metrics. We further refined its performance through hyperparameter tuning using Randomized Search and compared the top two ranked models for validation.

In the final phase, we categorized fare amounts into "High" and "Low" ranges and conducted a classification analysis to differentiate between these categories.

The project is a code-along adaptation of a tutorial by Misra Turp on YouTube, originally designed for January 2019 data. I have updated the analysis to use January 2024 data and implemented additional improvements, such as handling missing rows and refining the preprocessing steps.

Data source: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
