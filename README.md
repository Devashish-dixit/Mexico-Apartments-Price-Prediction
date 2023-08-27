# Mexico Apartment Price Prediction

This notebook walks through the process of predicting apartment prices in Mexico. Below are the key highlights of our analysis:

## Data Preparation
- Data was prepared using the `wrangle` function to clean and organize it for analysis.

## Data Exploration
- A histogram was created to visualize the distribution of apartment prices, providing an overview of the dataset's central tendencies and potential outliers.
- A scatter plot illustrated the relationship between apartment prices and their sizes, allowing us to explore the correlation between these variables.
- A Mapbox scatter plot displayed apartment locations, color-coded by price, helping us understand the geographic distribution of apartment prices.

## Data Modeling
- The dataset was split into a feature matrix and target vector, preparing it for machine learning.
- A baseline Mean Absolute Error (MAE) was calculated to assess the performance of our predictive model.

## Machine Learning
- A pipeline was created, comprising <OneHotEncoder> and <SimpleImputer> transformers, along with <Ridge Regression> as the regularization model.
- The model's Mean Absolute Error (MAE) score was computed and statistically validated, ensuring its reliability and predictive power.
- Predictions were generated for the test data, providing insights into apartment price estimates.

## Model Interpretation
- To understand the most influential factors affecting apartment prices, a horizontal bar chart was created, showcasing the top 10 coefficients from our Ridge Regression model.

This notebook guides you through the entire process of predicting apartment prices in Mexico, from data preparation to model interpretation, with a focus on transparency and meaningful insights.
