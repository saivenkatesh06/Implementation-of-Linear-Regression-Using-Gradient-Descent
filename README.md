# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import NumPy and Matplotlib libraries.
2. Initialize the dataset and regression parameters.
3. Calculate predicted values and compute the gradients.
4. Update slope and intercept using Gradient Descent for several iterations
5. Predict the profit and display the regression graph.

## Program:
```
/*
import numpy as np
import matplotlib.pyplot as plt

# Dataset
X = np.array([1, 2, 3, 4, 5], dtype=float)
Y = np.array([100, 200, 300, 400, 500], dtype=float)

# Initialize parameters
m = 0
c = 0
learning_rate = 0.01
epochs = 1000
n = len(X)

# Gradient Descent
for i in range(epochs):
    Y_pred = m * X + c

    dm = (-2/n) * sum(X * (Y - Y_pred))
    dc = (-2/n) * sum(Y - Y_pred)

    m = m - learning_rate * dm
    c = c - learning_rate * dc

# Predict profit
city = 6
profit = m * city + c

print("Predicted Profit:", profit)

# Plot graph
plt.scatter(X, Y, color='blue')
plt.plot(X, m*X + c, color='red')
plt.xlabel("City")
plt.ylabel("Profit")
plt.title("Linear Regression using Gradient Descent")
plt.show() 
*/
```

## Output:
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/de35d758-f2c9-4f8d-90b7-0ed5cb561314" />



## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
