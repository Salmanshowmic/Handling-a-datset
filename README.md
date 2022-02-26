# Handling-a-datset

Datset file: heart failur classification dataset (Uploaded in the repository)

Here, I showed some ways of handling a dataset for further uses.

MinMaxScaler: Transform features by scaling each feature to a given range. This estimator scales and translates each feature individually such that it is in the given range on the training set, e.g. between zero and one.

For each value in a feature, MinMaxScaler subtracts the minimum value in the feature and then divides by the range. The range is the difference between the original maximum and original minimum.The default range for the feature returned by MinMaxScaler is 0 to 1.

Heat map & Correlation map

train_test_split : A function in Sklearn model selection for splitting data arrays into two subsets: for training data and for testing data. With this function, you don't need to divide the dataset manually. By default, Sklearn train_test_split will make random partitions for the two subsets.
