## Gradient Descent and Linear Regression

Gradient Descent is a widely-used optimization algorithm that is often used in machine learning to train models such as Linear Regression. Linear Regression is a natural approach to a regression task, where the goal is to predict a continuous output variable based on one or more input variables. The model is based on a linear relationship between the input variables and the output variable, which is represented by a line in two dimensions, or a hyperplane in higher dimensions.

Linear Regression is a parameterized model, which means that it has a set of parameters (weights and biases) that need to be learned from the data. The model is trained using the Gradient Descent algorithm, which iteratively updates the parameters in the direction of the steepest descent of the loss function. The loss function measures the difference between the predicted output and the true output for each example in the training data, and the goal of the training process is to minimize this difference.

Like the Perceptron, Linear Regression is a single-neuron model that can be viewed as a simplified version of a neural network. However, while the Perceptron is primarily used for binary classification tasks, Linear Regression is used for regression tasks, where the output variable is continuous.

In summary, Gradient Descent and Linear Regression are natural approaches to regression tasks, and are widely used in machine learning. Linear Regression is a parameterized model that can be trained using Gradient Descent to learn the optimal set of weights and biases. While both Linear Regression and the Perceptron are single-neuron models, they are used for different tasks - Linear Regression for regression, and the Perceptron for binary classification.

Within the notebook you may find an explanation of how the model works as well as an implementation and application to the cbb dataset.
