# student_drop_out_prediction

## Merge Data
Combining finance, student progress and statics (30 csv files) in different semesters by Training and Testing as df_train and df_test.

## Cleaning values
1. NA into -1: information are missing
2. NA into 0: financial records
3. NA into unknown, for string columns

## EDA & Feature Engineering
1. Conduct normality diagnosis and perform necesaary log transformation.
2. Conduct wilcoxon rank sum test on continuous variables
3. Conduct Chi-Square test on categorical variables.

## Models
Implemented SVM, Naive Bayes, Logistic Regression, Decision Trees, Random Forest, and XGBoost.
