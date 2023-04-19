# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?resource=download](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?resource=download)
The  dataset are related to red variant of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones)

Number of Instances: 1599

Number of Attributes: 12

## Final Result Table

	Sample	Best Accuracy	Best Kernel	Best Nu	Best Epsilon
0	1	0.54	rbf	1.15	6.76
1	2	0.54	rbf	3.67	2.96
2	3	0.52	rbf	8.03	2.40
3	4	0.55	rbf	7.24	5.49
4	5	0.58	rbf	2.96	3.05
5	6	0.51	rbf	0.60	1.93
6	7	0.57	rbf	4.97	3.04
7	8	0.55	rbf	4.86	1.19
8	9	0.57	rbf	3.91	2.45
9	10	0.57	rbf	7.51	2.50

## Convergence Graph
![graph](https://github.com/rdevgarg/Parameter_optimization_of_SVM/blob/main/graph.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 4 has the best accuracy of 0.58 having kernel = rbf, Nu = 2.96 and Epsilon = 3.05.

## Written By
Name : Raghav Garg
  
Roll No. : 102003413

Sub-Group: 3CO13
