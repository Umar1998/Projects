In this project i have discussed the basics of **decision tree algorithm using titanic dataset**.

I have also tuned some  Hyperparameters just for illustration purpose

When we define the model, we can specify the hyperparameters.

In practice, the most common ones are:

**max_depth**: The maximum number of levels in the tree.\
**min_samples_leaf**: The minimum number of samples allowed in a leaf.\
**min_samples_split**: The minimum number of samples required to split an internal node.

For example, if we define a model where the maximum depth of the trees max_depth is 7, and the minimum number of elements in each leaf min_samples_leaf is 10.

>>> model = DecisionTreeClassifier(max_depth = 7, min_samples_leaf = 10)
