# Linear regression
In this notebook, we created a linear regression model represented by the equation:

                                            f(w, b)(x) = wx + b
To make our model fit our data well, we needed to find the best values for w and b.

We used a cost function J(w, b) to measure how well the model fits the data. The goal was to minimize this cost function by adjusting w and b.

To find the best w and b, we used an algorithm called gradient descent:

Gradient descent iteratively updates the parameters in the direction of the steepest decrease in the cost function.

At each iteration, the gradients of the cost function with respect to each parameter (∂J/∂w and ∂J/∂b) are computed.

The parameters (w, b) are then adjusted by subtracting a fraction of the gradient multiplied by a chosen learning rate, which controls the size of each update.

This process continues until convergence, where the change in the cost function becomes negligible or reaches a predefined threshold.

