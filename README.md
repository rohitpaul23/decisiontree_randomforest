# decisiontree_randomforest

Worked on Bank Marketing dataset. We have been provided with a pre-defined set of test, train and validation of dataset to work with. 
In this dataset, the first row represents the labels of each column such that the last column represents whether the client subscribed (y/n) and 
following that, each row represents an example. We have to implement the decision tree algorithm for predicting whether client subscribed a term deposit
Concepts used:
1. Used mutual information as the criteria for selecting the attribute to split on
2. Used the concept of gain ratio (= gain(x)/split_info(x)) where gain(x)==mutual info(x) to split the attributes
3. Random Forests an extensions of decision trees, where we grow multiple decision trees in parallel on bootstrapped samples constructed from the 
original training data.
