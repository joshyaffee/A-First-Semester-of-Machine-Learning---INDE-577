## K-Nearest Neighbors

K-Nearest Neighbors (KNN) is a simple but effective nonparametric algorithm used for classification and regression tasks. The basic idea behind KNN is to classify new data points or make predictions based on the "closeness" to existing data points in the training set. The algorithm works by computing the distance between a new data point and each point in the training set. The K nearest neighbors are then selected, and the majority class or the mean value of their target variable is used as the prediction for the new data point.

KNN is a nonparametric algorithm, which means that it does not make any assumptions about the underlying distribution of the data. Instead, it relies solely on the data to make predictions. This can be an advantage in cases where the relationship between the input and output variables is complex or nonlinear.

KNN can be used in a variety of contexts, such as image recognition, speech recognition, and recommendation systems. It can be particularly effective when the decision boundary between classes is irregular or non-linear. However, KNN can be computationally expensive for large datasets, and it may not perform well when the dataset has many irrelevant features or noisy data points.

In summary, K-Nearest Neighbors is a simple but effective nonparametric algorithm used for classification and regression tasks. It works by selecting the K nearest neighbors based on the distance between a new data point and existing data points in the training set. KNN is particularly useful in cases where the decision boundary between classes is irregular or non-linear. However, it may not perform well with large datasets or noisy data as we will see in the notebook

Within the notebook you may find an explanation of how the model works as well as an application to the cbb dataset.
