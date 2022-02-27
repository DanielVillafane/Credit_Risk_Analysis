# Credit_Risk_Analysis

## Overview
In an effort to predict credit risk we utilizied machine learning tools.

We used the following ML algoritms for our analysis:

RandomOverSampler, SMOTE, ClusterCentroids, Smottteen, BalancedRandomForectClassifier, and EasyEnsembleClassifier.


## Results:

### RandomOverSampler model
![oversample](/resources/oversample.png)
--- The balanced accuracy score is 62.5%.
--- The high risk precision is 1%  with 61% sensitivity.
--- The low risk precision is 100% with 67% sensitivity.


### SMOTE model
![smote](/resources/smote.png)
--- The balanced accuracy score is 64%.
--- The high risk precision is 1%  with 69% sensitivity/recall.
--- The low risk precision is 100% with 54% sensitivity/recall.


### ClusterCentroids model
![cluster](/resources/cluster.png)
--- The balanced accuracy score is 53%.
--- The high risk precision is 1%  with 61% sensitivity/recall.
--- The low risk precision is 100% with 45% sensitivity/recall.


### SMOTEENN model
![smoteen](/resources/smoteen.png)
--- The balanced accuracy score is 61.5%.
--- The high risk precision is 1%  with 69% sensitivity/recall.
--- The low risk precision is 100% with 54% sensitivity/recall.


### BalancedRandomForestClassifier model
![randomforect](/resources/randomforest.png)
--- The balanced accuracy score is roughly 79%.
--- The high risk precision is 7%  with 91% sensitivity/recall.
--- The low risk precision is 100% with 94% sensitivity/recall.



### EasyEnsembleClassifier model
![easy](/resources/easy.png)
--- The balanced accuracy score is 92.5%.
--- The high risk precision is 7%  with 91% sensitivity/recall.
--- The low risk precision is 100% with 94% sensitivity/recall.

## Summary
The high risk precision across all models is concern. 
Sensitivity/recall numbers improved with both the Balance Random Forest Classiifer and Easy Ensemble Classifier. But high risk precision still remains a concern.
