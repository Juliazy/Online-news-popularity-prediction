# Online-news-popularity-prediction

## Overview
This is a project of online news popularity prediction. The dataset used is much smaller than the original dataset. Therefore, the result might be a little bit different from the results generated from original dataset. 

## programming environment 
Jupyter Notebook.
Strongly recommend use Jupyter Notebook from Anaconda3. 

## dataset
It is uploaded. 
```
OnlineNewsPopularityReduced.csv
```

## classifiers

There are totally 8 classifiers used in this project, including SVM, perceptron, RF, Decision Tree, logistics regression etc.

## Results
```
Test accuracy
```
Every classifier has a test accuracy for test set. Most of the accuracy is around 66%. Perceptron's result is the worst.
```
F1 score
```
F1 score is a evaluation method for the classifier. The higher the better.
```
ROC
```
Only SVM classifier with RBF kernel has ROC curve. Cross validation is used in SVM classifier. I generate the ROC for different number of folds. 

## appendix
For more details, please refer to my report.

