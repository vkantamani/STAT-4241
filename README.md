# STAT-4241
(CU) STAT 4241 Statistical Machine Learning

The original dataset contains expression levels of 24,187 genes for 97 patients - of which 46 patients relapse ("status" is 1) and 51 patients do not relapse ("status" is 0). 78 cases were used as the training set (34 relapse and 44 non-relapse) and 19 (12 relapse and 7 non-relapse) as the test set. 

We have pre-processed the data, normalized expression levels, and filtered genes using a p-value criterion. After this step, 4918 genes remain. Using the training set of 78 cases with 4918 predictors and a binary response, we use non-linear kernel SVM with recursive feature elimination to classify patient breast cancer status and predict on the test set with 56.8% accuracy, which demonstrates superior performance to KNN and Naive Bayes classification techniques.
