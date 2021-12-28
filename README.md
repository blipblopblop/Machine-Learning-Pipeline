# Machining-Learning-Pipeline
Building a machine learning pipeline to determine if the first stage of the Falcon 9 lands successfully. 

This begans with preprocessing to standardize the data, and then Train_test_split to split the data into training and testing. Using GridSearchCV, the best hyperparamters will be chosen to allow the given alogrithm to perform at its best with the training data. The best hyperparamter values are used to determine the model with the best accuracy using the training data. These models will be determined with the following supervised machine alogirthms: Logistic Regression, Support Vector machines, Decision Tree Classifier, and K-nearest neighbors, to finally output a confusion matrix with each respective model. 

