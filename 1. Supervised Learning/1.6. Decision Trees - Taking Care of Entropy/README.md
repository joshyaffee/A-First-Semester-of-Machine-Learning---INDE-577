## Decision Trees

Decision Trees are a nonparametric algorithm used for both classification and regression tasks. The basic idea behind Decision Trees is to partition the data into smaller and smaller subsets based on the values of the input variables, until the subsets become homogeneous in terms of the target variable. Each partitioning step is made based on a decision rule that maximizes the reduction in uncertainty about the target variable. The resulting tree-like structure is used to make predictions for new data points by traversing the tree from the root to a leaf node.

Decision Trees are particularly useful when there are nonlinear relationships between the input and output variables or when the decision boundary is irregular. They can also handle both categorical and numerical input variables, and they can easily handle missing data.

Entropy is a measure of the uncertainty or impurity of a set of data. In the context of Decision Trees, entropy is used to measure the impurity of a subset of data with respect to the target variable. The goal of each partitioning step is to minimize the entropy of the resulting subsets, which means that the subsets become more homogeneous in terms of the target variable.

Decision Trees can be used in a variety of contexts, such as credit risk analysis, customer segmentation, and medical diagnosis. However, they may not perform well when the data has many irrelevant features or when there are interactions between input variables that cannot be captured by a single decision rule. Additionally, Decision Trees can be prone to overfitting if the tree is too complex, which can be addressed by pruning or by using ensemble methods like Random Forests.

In summary, Decision Trees are a nonparametric algorithm used for both classification and regression tasks. They work by partitioning the data into smaller and smaller subsets based on decision rules that maximize the reduction in uncertainty about the target variable. Entropy is used to measure the impurity of the subsets, and the resulting tree-like structure is used to make predictions for new data points. Decision Trees are particularly useful when there are nonlinear relationships between input and output variables or when the decision boundary is irregular.

Within the notebook you may find an explanation of how the model works as well as an application to the cbb dataset.
