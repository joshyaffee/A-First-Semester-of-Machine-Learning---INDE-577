## Logistic Regression

Logistic Regression is a machine learning algorithm that is commonly used for binary classification tasks, where the goal is to predict whether an input belongs to one of two classes (for example, whether an email is spam or not). The algorithm is a clever way to predict the probability of an input belonging to a particular class, by using regression to model the relationship between the input variables and the binary output.

Logistic Regression is a parameterized model, which means that it has a set of parameters (weights and biases) that need to be learned from the data. The model is trained using a variant of the Gradient Descent algorithm, called the Logistic Regression Cost Function, which measures the difference between the predicted probability and the true probability for each example in the training data. The goal of the training process is to minimize this difference.

Logistic Regression can be viewed as a simplified version of a neural network, specifically a single-layer neural network with a sigmoid activation function. Like the Perceptron and Linear Regression, Logistic Regression is a single-neuron model. However, while Linear Regression is used for regression tasks, and the Perceptron is primarily used for binary classification tasks, Logistic Regression is specifically designed for binary classification tasks and is optimized to predict probabilities.

In summary, Logistic Regression is a clever way to predict probability by using regression, and is commonly used for binary classification tasks. It is a parameterized model that can be trained using the Logistic Regression Cost Function and Gradient Descent. Like the Perceptron and Linear Regression, it is a single-neuron model, but it is specifically designed for binary classification tasks and is optimized to predict probabilities.

Within the notebook you may find an explanation of how the model works as well as an implementation and application to the cbb dataset.
