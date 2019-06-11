# KNN-Classification-on-Iris-data-set
The first line imports iris data set which is already predefined in sklearn module. 
We import kNeighborsClassifier algorithm and train_test_split class from sklearn and numpy module for use in this program.

Then we encapsulate load_iris() method in iris_dataset variable. 
Further we divide the dataset into training data and test data using train_test_split method. The X prefix in variable denotes the feature values (eg. petal length etc) and y prefix denotes target values (eg. 0 for setosa, 1 for virginica and 2 for versicolor).

In the next line, we fit our training data into this algorithm so that computer can get trained using this data. Now the training part is complete.
Finally we find the test score which is the ratio of no. of predictions found correct and total predictions made.
