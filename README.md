Overview

This project is a practice implementation of Multiple Linear Regression to predict Index Price based on macroeconomic indicators such as Interest Rate and Unemployment Rate. The dataset contains economic data and is used to analyze trends in market performance.

Dataset

The dataset consists of the following columns:

Year: The year of data collection.

Month: The month of data collection.

Interest Rate (%): The prevailing interest rate at that time.

Unemployment Rate (%): The percentage of unemployed individuals in the labor force.

Index Price: The financial index value (e.g., stock market index).

Dependencies

Ensure you have the following Python libraries installed:

pip install pandas numpy scikit-learn seaborn matplotlib

Implementation Steps

Load the dataset into a Pandas DataFrame.

Preprocess the data (handling missing values, scaling if necessary).

Split the data into training and testing sets.

Train a Multiple Linear Regression model using sklearn.

Evaluate the model using metrics like R² score and Mean Squared Error (MSE).

Visualize relationships using seaborn.pairplot and sns.regplot.
