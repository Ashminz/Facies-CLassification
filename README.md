# Facies-CLassification
Facies classification is one of the most important tasks that geoscientists work on development and exploration projects. Sedimentary facies reflect particular physical, chemical, and biological condition that unit experienced during sedimentation process. To study these facies, rock samples are required. In this study, it is practiced to train various machine learning algorithms to predict facies from well log data. The dataset for this study comes from Hugoton and Panoma Fields in North America which was used in class exercise in The University of Kansas (Dubois et. al, 2007). It consists of log data of nine wells. We will use these log data to train supervised classifiers in order to predict discrete facies groups. All this implementation is based on scikit-learn libraries
These are:

Support vector machines (SVM)
Random forest classifier (RFC)
Multi-layer Perceptron classifier(Neural Network classifier, NNC)
K Nearest Neighbors Classifier (KNN)
Decision tree classifier (DT)
Logistic regression (LR)
![image](https://user-images.githubusercontent.com/76057261/169086432-2d1572c6-d9da-4f9b-b7c0-0537449278c5.png)

SVM, NNC, and KNN show better performance in test data(table E1).
When it comes to examining models with new data(blind well) all model performance drops (table E2)
