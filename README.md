# Machine Learning - Aprendizagem de Máquina - Assignment

## Objectives
The machine learning task, and inparticular the task of classification, can be approached using different principles and assumptions, which leads to different methods that can be implemented in different ways using a variety of hyperparameters. The general objective of this assignment is to demonstrate and understand advantages and disadvantages of different ML methods derived from different principles. For that, the students will take pairs of methods and look for (artificial) datasets that favour one or the other.

## Task
For each pair i of methods below (two methods A and B are mentioned) do the following:
+ Define two Python functions GAi and GBi that generate artificial classification datasets such that GAi tends to generate a dataset where method Ai is (significantly) better than method Bi, and GBi tends to generate a dataset where method Bi is significantly better than method Ai.

**Notes**: 
    - “Tends to” means “more often than not”. This can be measured by repeating each experiment 10 times. 
    - Methods are compared using AUC (area under the ROC curve). 
    - You can define hyperparameters for each exercise, but you can change them for the same methods in different exercises.

## Consider the following pairs of methods:
1. Logistic regression vs Nearest Neighbour
2. LDA vs Decision Tree
3. LDA vs. QDA
4. Logistic regression vs LDA
5. Nearest neighbour vs. decision tree
6. Decision tree vs Tree Boosting
7. SVM radial basis vs SVM linear Kernel
8. SVM radial basis vs SVM polynomial
9. MLP vs Logistic Regression
10. MLP vs Nearest Neighbour
11. MLP ReLu vs MLP sigmoid

## Actions:
+ For each pair try first a dataset with 2 descriptors. You only have to show results for the best datasets.
+ Visualize side by side the boundaries defined by each method. If you need datasets with more than 2 descriptors use tSNE for a 2 dimensional visualization.
+ Justify the results of each pair taking into account the characteristics of the dataset and of the methods/hyperparameters.
