
# Machine Failure Prediction

This notebook uses the dataset from [Kaggle: Machine Failure Prediction](https://www.kaggle.com/code/muhammadfaizan65/machine-failure-prediction-eda-modeling) for predicting machine failures.

The model implemented uses the **Stochastic Gradient Descent (SGD)** algorithm.

## Results

The confusion matrix shows that the classifier correctly predicted:

+ 96 instances of class 0 (no failure)

+ 77 instances of class 1 (failure)

It misclassified:

+ 9 instances of class 0 as class 1 (false positives)

+ 7 instances of class 1 as class 0 (false negatives)

Overall, the model demonstrates a high level of accuracy, with a balanced performance across both classes. The low number of false positives and false negatives indicates that the classifier is effectively distinguishing between the failure and non-failure cases.

