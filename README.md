# CreditCardFraud

Comparison of different machine learning algorithms

I have used 4 supervised machine learning algorithms to predict the test set. The train: test set ratio is 7:3. For each algorithm, I have tried to find out the best set of attributes in order to get the best result possible. The algorithms used are as follows:

•	SUPPORT VECTOR MACHINE: SVMs are a set of supervised learning methods used for classification, regression and outlier detection. The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space (N — the number of features) that distinctly classifies the data points. Our objective is to find a plane with the maximum margin i.e. the maximum distance between data points of the two classified classes.

•	DECISION TREE MODEL: A decision tree is a flowchart-like tree structure where an internal node represents feature (or attribute), the branch represents a decision rule, and each leaf node represents the outcome. The topmost node in a decision tree is known as the root node. It learns to partition on the basis of the attribute value. It partitions the tree in recursively manner call recursive partitioning. This flowchart-like structure helps in decision making. Here, I have taken into consideration various depths (1-10) to find out which one gives the best accuracy and F1 score and compared that with other models.

•	RANDOM FOREST CLASSIFIER: A forest is comprised of trees. It is said that the more trees it has, the more robust a forest is. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance. Here, I have taken into consideration various depths (1-10) to find out which one gives the best accuracy and F1 scores and compared that with other models.

•	K-NN CLASSIFIER: K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories. This means when new data appears then it can be easily classified into a well suited category by using K- NN algorithm. Here, I have taken into consideration various depths (1-15) to find out which one gives the best accuracy and F1 scores and compared that with other models.
According to my model, the best performance has been achieved by random forest classifier on the basis of both accuracy and F1 score and the worst performance is by K-NN classifier.
