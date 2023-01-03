# Fair-Explainable-Analytics-Seminar
Comparing Tabular Data Generation and Imputation

First, was executed an analysis of the data set (in the folder data - adult_train and adult_test) on "Data_Analysis.ipynb" and removed its missing values (in the folder data - D_train and D_test). The last one were the sets to then be used.

Secondly, some values of the test set were randomly removed (in the folder data_removed) and the MissForest was trained in the train set. Then, the values removed were imputed by the MissForest trained and finally, was evaluated that imputation, comparing the original values with the imputed values. This was done in 3 different cases in the codes "MissForestImputation_caseX.ipynb".

Thirdly, our supervisor did the imputation with the GReaT approach from the test sets in the folder data_removed and sent the test set with the imputed values to us (in the folder data_great_impute) to then be done the evaluation. This was done in the codes "GReaT_code_caseX.ipynb".
