# Problem Statement 
A machine has multiple specifications which are given in the dataset and we have to predict the Failure Type encountered by that machine. We have to predict which kind of failure will the machine may encounter. 
## Dataset

The dataset used is the Predictive Maintenance (https://www.kaggle.com/shivamb/machine-predictive-maintenance-classification) from Kaggle. 

Task : Classification of Failure Types

Target : Failure Type and Target

The 3 class labels of Failure Type are:
<br>

**1. No Failure :** Machine with given specifications does not undergo any failure.
<br>
**2.Heat Dissipation Failure :** Machine with given specifications undergoes a Heat Dissipation Failure.
<br>
**3. Others :** Machine with given specifications undergoes a Failure of any other type.

Note: Others consists of Power Failure,Overstrain Failure,Tool Wear Failure,Random Failures only.

The 2 class labels of Target are:
<br>

1. 0 :  No failure happens
2. 1 :  Failure happens
<br>
## Model(s) Used

Various classification models were tried on the dataset as follows:
1. K-Nearest Neighbours(KNN)
2. Logistic Regression
3. Decision Tree 
<br>

**K-Nearest Neighbours:** a Supervised Learning Algorithm most commonly used for classification. It uses the training data to form groups or clusters of every label or category. When unclassified data is predicted it takes the k-nearest neighbours and chooses the label of majority.

**Logistic Regression:** a Supervised Learing Algorithm generally used for binary classification problems. However, it can be used for multiclass classification problems using One v/s all methodology.

**Decision Tree:** a tree-like flowchart representation with each branch resembling the outcome of a test and leaf node is a class label.

## Future Work
Identifying overfitting in the model and various other parameters in the used classification algorithm for reducing overfitting.
