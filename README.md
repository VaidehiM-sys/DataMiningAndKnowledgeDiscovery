# Data Mining And Knowledge Discovery
 
## 1. Wine Quality Data Analysis

Data Analysis performed on Red Wine and White Wine dataset to model wine quality based on physicochemical tests or measurements. Each wine sample is described by Eleven sensor measurements (or features) and One output label (quality level). The eleven attributes include: 
  * 1 - fixed acidity
  * 2 - volatile acidity
  * 3 - citric acid
  * 4 - residual sugar
  * 5 - chlorides
  * 6 - free sulfur dioxide
  * 7 - total sulfur dioxide
  * 8 - density
  * 9 - pH
  * 10 - sulphates
  * 11 – alcohol
 
 The output label represents the level of quality classified by wine experts. 
   * 12 - quality (score between 0 and 10)

More details about these 12 attributes can be found in the reference: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

Histograms, boxplots, scatterplots and between-sample similarity matrices over each of the two datasets were plotted. 

## 2. Decision Tree and K-nearest Neighbor for Wine Quality Dataset

Implementation of Decision Tree and K-nearest Neighbor Classification on the Wine Quality dataset.

Calculation of GINI index, misclassification error and entropy of this sample set.

Calculation of the confusion matrix for a binary classifier.

Traning and testing of KNN model with values K=1,3,5,7 and 9. 

Calculation of ROC curves and AUC values of the five KNN models over testing samples of positive class. 
