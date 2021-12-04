# STAT-4241
(CU) STAT 4241 Statistical Machine Learning

For this project, we will work on the data set collected from a study of breast cancer:

breast_cancer_train.csv

The original dataset contains expression levels of 24,187 genes for 97 patients, 46 relapse ("status" is 1) and 51 non-relapse ("status" is 0). 78 cases were used as the training set (34 relapse and 44 non-relapse) and 19 (12 relapse and 7 non-relapse) as the test set. The dataset has been preprocessed. We normalized the expressions levels and filtered the genes by a p-value criterion. After this step, 4918 genes remain. For this project, I only upload the training set, which contains 78 cases, with 4918 predictors and a binary response.

Task:
1. Choose an appropriate method we discussed this semester and build a model to predict the patient's statue (relapse or non-relapse).
2. Evaluate the model performance by cross-validation.
3. Wrap your model in a function, which takes gene expression levels as input, and return the prediction of patients' status.
