# LetterRecognition_Project
INTRODUCTION:  

The data contains 26 English alphabets as classes, so it's a multiclass classification problem with 26 classes. Each record in the data contains 16 numeric attributes which were extracted from an image containing an alphabet. We have 20,000 such records generated from 20 different fonts and 26 English letters.
The objective is to identify each of the english characters based on these 16 features namely ['x-box', 'y-box', 'width', 'high', 'onpix', 'x-bar', 'y-bar', 'x2bar', 'y2bar', 'xybar', 'x2ybr', 'xy2br', 'x-ege', 'xegvy', 'y_ege', 'yegvx']. 

Pre-processing of the data:

The dataset used in this project is already processed and cleaned. There are no null values, and no imputation or dropping of rows or columns is required. As a result, the data can be used directly in the project.

The following models are implemented in this project:

Dummy Classifier

Linear Model

Decision Tree

Random Forest

K-Nearest Neighbors

SVM with linear kernel

SVM with non-linear kernel

Each model has its own method of categorizing data, and their advantages and disadvantages are discussed in the reference links.

Variable Selection:


The dataset has 16 features, and to select the best features, two feature selection methods are applied:

Lasso technique: This method uses L1 regularization to add a penalty equal to the absolute value of the magnitude of the coefficients. The Lasso technique has selected 13 important features required for modeling.

Bi-directional elimination (BDE) or Stepwise selection: This method is used to reduce the number of input features by removing unimportant ones. BDE has selected 14 features.

Conclusion:


In conclusion, the objective of this project is to classify 26 English letters based on 16 features using SVM. The SVM model with a non-linear kernel performed the best among all other models. Feature selection methods such as Lasso and Bi-directional elimination were used to select the best features. The dataset is preprocessed and cleaned, and no further processing was required.

For more information, please refer to the reference links.

References
[1] https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyClassifier.html

[2] https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

[3] https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html

[4] https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

[5] https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html

[6] https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html

[7] https://archive.ics.uci.edu/ml/datasets/Letter+Recognition

[8] https://pdfs.semanticscholar.org/1a21/bf8cbfc054c0497d9e46b83be7b8f2b40eb7.pdf
