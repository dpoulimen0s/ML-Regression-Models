# Regression Model Comparison

This repository contains the implementation and improvement of four regression models: Linear Regression, Random Forest Regression, Support Vector Regression, and Bagging Regression. The primary goal was not only to create these models but also to enhance their performance and compare them.

## Academic Assignment

This project was undertaken as part of a machine learning assignment during the 3rd year of the bachelor's degree at Newcastle University.

## Model Development and Improvement

I started with a provided notebook and iteratively improved each model. The key enhancement technique used was `GridSearchCV`, leveraging K-fold validation to find optimal hyperparameters for each model. The chosen hyperparameters resulted in improved accuracy and reduced Mean Square Error (MSE). Notably, the Bagging Regressor showed the most significant improvement, with a 13.5% increase in accuracy.

### Model Performance

- **Random Forest Regression**: Achieved the highest accuracy score of 81.23% with an MSE of 0.1774.
- **Bagging Regression**: Demonstrated the most improvement, with a 13.5% accuracy boost.
- **Support Vector Regression**: Improved accuracy and reduced MSE through hyperparameter tuning.
- **Linear Regression**: No significant improvement due to prior outlier detection and removal.

## Plots and Visualization

I created several plots to visually assess model performance:

1. **Scatterplots**: A table summarizing test accuracy, train accuracy, and MSE for each model.
2. **Regression Line Plots**: Demonstrating the regression line for each model.
3. **Fluctuation Comparison Graphs**: Illustrating how predicted data fluctuates compared to actual data.
4. **Boxplot**: Visualizing metric values (test accuracy, train accuracy, MSE) for each model.

## Usage

To reproduce the results, follow these steps:

1. Install required dependencies using `requirements.txt`.
2. Run the provided notebook.
3. Explore the generated plots to understand model performance.

## Contributors

- Dimitrios Poulimenos ([dpoulimen0s](https://www.linkedin.com/in/dpoulimenos/)) - Initial work 
