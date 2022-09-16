# Support-Vector-Machine-ML-Model
Support Vector Machine (SVM) is a classification technique. The objective of SVM is to categorize data into two classes. It does so by finding a separating hyperplane(decision boundary), where the distance itself and the closest data points for both categories is maximized. This hyperplane splits the data in the best possible way as shown in the diagram below.


![image](https://github.com/rkadey/Support-Vector-Machine-ML-Model/blob/main/vlcsnap-2022-09-16-00h32m53s884%20(2).png?raw=true)

# Terminologies
## C Parameter
The C parameter allows you to decide how much you want to penalize misclassified points.The default value of the C parameter is 1 however, this value can be  adjusted to compare the model score.
![image](https://github.com/rkadey/Support-Vector-Machine-ML-Model/blob/main/vlcsnap-2022-09-16-00h46m14s492%20(2).png)

## Multiple Classes.
When your data have two classes, we can fit the model by default values. If there are more than two classes in the data, we use the decision_function_shape parameter and set it to ovr or ovo. ovr means One vs. Rest. It classifies one group with the rest of the data and then move on to the second group and classify them against the rest of the data and put the remaining of the data into another group.
ovo compares all the classes separately and create a hyperplane for each one of them.
