
# Linear Regression with Minimum Sum Squares Technique

This code demonstrates how to perform linear regression using the Minimum Sum Squares Technique (MSSE) to obtain the equation of the line that best fits a set of training data points. It also includes a section to add noise to the data and observe its effect on the regression model.

## Part I: Original Linear Equation

- Define a linear equation of one variable: \( Y = WX + C \), where \( W \) represents the slope and \( C \) represents the y-intercept.
- Select 5 different values for \( X \) (\( X_1, X_2, X_3, X_4, X_5 \)) and calculate their corresponding \( Y \) values using the defined linear equation.
- Use the \( X \) and \( Y \) values as the training data and apply MSSE to obtain the equation of the line that best fits the training data.
- Output is positive for class 1 and negative for class 2, making the model suitable for input.

## Part II: Linear Equation with Added Noise

- Repeat the previous steps after adding some noise to the original linear equation.

## Code Explanation

- The code is written in Python and utilizes libraries such as NumPy and Matplotlib.
- It generates random values for \( X \) and calculates corresponding \( Y \) values based on the original linear equation.
- Linear regression is performed using MSSE to obtain the best-fit line for the training data.
- The process is repeated with added noise to observe its effect on the regression model.

## Instructions for Running the Code

1. Ensure you have Python installed on your system.
2. Install the required libraries (`numpy`, `matplotlib`) if not already installed.

![Linear Regression Image](Linear_regression-with-MSSE/img/MSSE.png)

