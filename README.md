Predicting Property Prices Using Regression Coefficients
This project demonstrates how to use regression coefficients to estimate property prices based on various characteristics. The data used is derived from the Boston Housing Dataset, and the focus is on building and interpreting a linear regression model, including applying transformations to improve performance.

Features and Highlights
Dataset:

The dataset includes features like crime rate (CRIM), number of rooms (RM), property tax (TAX), and proximity to the Charles River (CHAS).
The target variable is the median property price (PRICE).
Preprocessing:

Performed transformations on the target variable (PRICE) using logarithmic scaling to handle skewness and improve model accuracy.
Model:

Trained a Linear Regression model using the Scikit-learn library.
Evaluated the model with R-squared (R²) for both training and test datasets.
Analysis:

Explored the relationship between features and target using coefficients.
Visualized the residuals to assess model performance.
Use Case:

Predicted the price of a property using average feature values and specific user-defined characteristics (e.g., proximity to the river, number of rooms, and pollution levels).
Key Steps
Exploratory Data Analysis (EDA):

Checked for skewness in the dataset and applied necessary transformations.
Visualized feature distributions and their relationships to PRICE.
Training the Model:

Split the dataset into training and testing sets.
Fit a linear regression model and computed R² for both sets.
Feature Importance:

Extracted coefficients to analyze the impact of each feature on property prices.
Prediction:

Estimated property prices based on user-defined inputs.
Applied the inverse log transformation to convert predictions to the original price scale.
Technologies Used
Programming Language: Python
Libraries:
Pandas and NumPy for data manipulation.
Matplotlib and Seaborn for visualization.
Scikit-learn for model training and evaluation.
