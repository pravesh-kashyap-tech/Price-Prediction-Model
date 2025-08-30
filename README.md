# Price Prediction Model
Price Prediction Model Using Linear Regression Model
<br> <br>
🏠 House Price Prediction Project
📌 Project Overview

This project demonstrates how to predict house prices based on several key features using Linear Regression. The dataset data_set.csv includes synthetic house data with features such as:

Rooms – Number of rooms in the house

Area – Size of the house in square feet

Location – Categorical variable (Downtown, Suburb, Rural)

Age – Age of the house in years

Price – Target variable (house price in $)

The project uses Python’s pandas, numpy, matplotlib, and scikit-learn libraries to perform data preprocessing, model training, evaluation, and visualization.

⚙️ Features

Load and explore the dataset

Preprocess the data including one-hot encoding for categorical variables

Split dataset into training and testing sets

Train a Linear Regression model to predict house prices

Evaluate model performance using Mean Squared Error (MSE) and R² score

Visualize actual vs predicted house prices

🛠️ Technologies Used

Python 3

pandas – Data handling and preprocessing

numpy – Numerical operations

matplotlib – Data visualization

scikit-learn – Machine Learning (Linear Regression)

📊 Model Information

The Linear Regression model is a simple yet effective algorithm for predicting house prices. It assumes a linear relationship between the features (Rooms, Area, Location, Age) and the target (Price). Key details include:

Coefficients: Show the impact of each feature on the house price

Intercept: Base price when all features are zero

R² Score: Measures how well the model explains the variance in prices

Mean Squared Error (MSE): Measures average squared difference between predicted and actual prices

The model can be used to predict house prices for new properties by providing their features.
