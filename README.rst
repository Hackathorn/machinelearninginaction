Machine Learning in Action 
==========================

This is the source code to go with "Machine Learning in Action" by Peter Harrington published by Manning Inc.
The official page for this book can be found here: http://manning.com/pharrington/  All the code examples were working on 
Python 2.6, there shouldn't be any problems with the 2.7.  NumPy will be needed for most examples.  If you have trouble 
running any of the examples us know on the Forum for this book: http://www.manning-sandbox.com/forum.jspa?forumID=728.If you 
want to run these on some other version of Python say--3.0 or IronPython, feel free to fork the code.   

Part 1 Classification

1. Machine learning basics
1.1. What is machine learning?
1.2. Key terminology
1.3. Key tasks of machine learning
1.4. How to choose the right algorithm
1.5. Steps in developing a machine learning application
1.6. Why Python?
1.7. Getting started with the NumPy library
1.8. Summary

2. Classifying with k-Nearest Neighbors
2.1. Classifying with distance measurements
2.2. Example: improving matches from a dating site with kNN
2.3. Example: a handwriting recognition system
2.4. Summary

3. Splitting datasets one feature at a time: decision trees
3.1. Tree construction
3.2. Plotting trees in Python with Matplotlib annotations
3.3. Testing and storing the classifier
3.4. Example: using decision trees to predict contact lens type
3.5. Summary

4. Classifying with probability theory: naïve Bayes
4.1. Classifying with Bayesian decision theory
4.2. Conditional probability
4.3. Classifying with conditional probabilities
4.4. Document classification with naïve Bayes
4.5. Classifying text with Python
4.6. Example: classifying spam email with naïve Bayes
4.7. Example: using naïve Bayes to reveal local attitudes from personal ads
4.8. Summary

5. Logistic regression
5.1. Classification with logistic regression and the sigmoid function: a tractable step function
5.2. Using optimization to find the best regression coefficients
5.3. Example: estimating horse fatalities from colic
5.4. Summary

6. Support vector machines
6.1. Separating data with the maximum margin
6.2. Finding the maximum margin
6.3. Efficient optimization with the SMO algorithm
6.4. Speeding up optimization with the full Platt SMO
6.5. Using kernels for more complex data
6.6. Example: revisiting handwriting classification
6.7. Summary

7. Improving classification with the AdaBoost meta-algorithm
7.1. Classifiers using multiple samples of the dataset
7.2. Train: improving the classifier by focusing on errors
7.3. Creating a weak learner with a decision stump
7.4. Implementing the full AdaBoost algorithm
7.5. Test: classifying with AdaBoost
7.6. Example: AdaBoost on a difficult dataset
7.7. Classification imbalance
7.8. Summary

Part 2 Forecasting numeric values with regression

8. Predicting numeric values: regression
8.1. Finding best-fit lines with linear regression
8.2. Locally weighted linear regression
8.3. Example: predicting the age of an abalone
8.4. Shrinking coefficients to understand our data
8.5. The bias/variance tradeoff
8.6. Example: forecasting the price of LEGO sets
8.7. Summary

9. Tree-based regression
9.1. Locally modeling complex data
9.2. Building trees with continuous and discrete features
9.3. Using CART for regression
9.4. Tree pruning
9.5. Model trees
9.6. Example: comparing tree methods to standard regression
9.7. Using Tkinter to create a GUI in Python
9.8. Summary

Part 3 Unsupervised learning

10. Grouping unlabeled items using k-means clustering
10.1. The k-means clustering algorithm
10.2. Improving cluster performance with postprocessing
10.3. Bisecting k-means
10.4. Example: clustering points on a map
10.5. Summary

11. Association analysis with the Apriori algorithm
11.1. Association analysis
11.2. The Apriori principle
11.3. Finding frequent itemsets with the Apriori algorithm
11.4. Mining association rules from frequent item sets
11.5. Example: uncovering patterns in congressional voting
11.6. Example: finding similar features in poisonous mushrooms
11.7. Summary

12. Efficiently finding frequent itemsets with FP-growth
12.1. FP-trees: an efficient way to encode a dataset
12.2. Build an FP-tree
12.3. Mining frequent items from an FP-tree
12.4. Example: finding co-occurring words in a Twitter feed
12.5. Example: mining a clickstream from a news site
12.6. Summary

Part 4 Additional tools

13. Using principal component analysis to simplify data
13.1. Dimensionality reduction techniques
13.2. Principal component analysis
13.3. Example: using PCA to reduce the dimensionality of semiconductor manufacturing data
13.4. Summary

14. Simplifying data with the singular value decomposition
14.1. .1 Applications of the SVD
14.2. Matrix factorization
14.3. SVD in Python
14.4. Collaborative filtering–based recommendation engines
14.5. Example: a restaurant dish recommendation engine
14.6. Example: image compression with the SVD
14.7. Summary

15. Big data and MapReduce
