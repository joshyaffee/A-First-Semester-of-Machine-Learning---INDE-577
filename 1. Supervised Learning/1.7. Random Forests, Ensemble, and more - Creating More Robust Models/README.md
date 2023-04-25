## More Robust Models

- Random Forests: Random Forests are actually an ensemble method (see generalized summary below) that combines multiple decision trees. Each decision tree is trained on a random subset of the training data and a random subset of the input features. The resulting predictions of the individual trees are then aggregated to produce a final prediction. This approach helps to reduce overfitting and improve generalization performance, since each tree is trained on a slightly different subset of the data.

- Boosting: Boosting is a technique used in ensemble methods that combines multiple weak learners into a strong learner. Each weak learner is trained on a subset of the training data, and the weights of the misclassified examples are increased for each subsequent weak learner. The final prediction is then determined by aggregating the predictions of all the weak learners. This approach helps to improve performance by focusing on the examples that are most difficult to classify.

- Bootstrapping: Bootstrapping is a resampling technique that involves randomly sampling the data with replacement. This creates multiple datasets that are each slightly different, which can be used to train multiple models that can be combined into an ensemble. Bootstrapping helps to reduce the variance of the estimator by averaging over multiple models that are trained on slightly different subsets of the data.

- Ensemble Methods: Ensemble methods in general combine the predictions of multiple models to produce a final prediction. This can improve performance by reducing the variance of the estimator and improving generalization performance. The models in the ensemble can be trained on different subsets of the data, using different algorithms, or with different hyperparameters. Combining the predictions of these models can help to overcome the weaknesses of individual models and produce a more robust estimator.

In summary, resampling, combining model strengths, and leveraging the power of multiple models are the underlying ideas behind Random Forests, Boosting, Bootstrapping, and Ensemble Methods. These techniques help to create more robust models by reducing the variance of the estimator, improving generalization performance, and overcoming the weaknesses of individual models.

Within the notebook you may find a much more indepth explanation of how these methods work. To see them in action, please go to the next stop of the tour, 1.8 to see the healthcare dataset being put to use.
