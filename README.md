# breast-cancer-gene-signature
<br>
This dataset is from a breast cancer study published by van't Veer et al. in 2002, available in bioconductor.The motivation is to find gene signature to predict whether a breast cancer patient will have metastases within five years or not. Traditional predictors such as lymph node status, tumor size, and tumor grade often fail to predict metastasis accurately. A significant portion of patients recieiving chemotherapy would have survived without it. This study used gene expression array, supervised classification, and leave-one-out cross-validation to identify a 70-gene signature. This gene signature outperformed all other clinical parameters in predicting disease outcomes.
<br>
<br>
I used R and bioconductor for data analysis. During data exploration, I examined the connection between disease outcome and estrogen receptor status, BRCA mutation, lymph node, and  tumor grade, with statistical tests and ggplot. For modeling, I used randomforest and svm. After tuning parameters, I plotted ROC surve. SVM is clearly better than random forest.
