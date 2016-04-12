# breast-cancer-gene-signature

This dataset is from a breast cancer study published by van't Veer et al. in 2002 and van de Vijver et al, available in bioconductor.The motivation is to find gene signature to predict whether a breast cancer patient will have metastases within five years or not. The traditional predictors such as lymph node status, tumor size, and tumor grade often fail to predict metastasis accurately. A significant portion of patients recieiving chemotherapy would have survived without it. This study used gene expression array to identify a 70-gene signature. With more accurate prediction of metatases, overtreatment of chemotherapy can be reduced.
<br>
<br>
I used R and bioconductor for data analysis. After some data exploration with estrogen receptor status, BRCA mutation, lymph node, and  tumor grade, with statistical tests and ggplot, I used randomforest and svm for supervised classification. After tuning parameters, I plotted ROC surve. SVM is clearly better than random forest.
