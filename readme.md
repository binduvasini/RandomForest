Random Forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.

* The fit function creates a number of decision trees on randomly-generated subsets of the data and randomly-selected features from those available during training.

* The predict function hypothesizes the label of each item in the input by determining the most populous label from among the trained trees.