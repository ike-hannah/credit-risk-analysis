# credit-risk-analysis

## Overview of the analysis: 
The purpose of this analysis was to evaluate differesnt kinds of machine learning algorithms and to pick one that produces the most accurate results in order to assess cresit risk. 

## Results:
Native Oversampling
<br>
![NativeRandomOversampling](https://user-images.githubusercontent.com/65744738/169933956-c2f03a1b-aaed-4361-8ed7-464604d4c51b.png)
<br>
Balanced Accuracy: 0.6497536370265621
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.62
Recall Low: 0.68

SMOTE oversampling
<br>
![SMOTEoversampling](https://user-images.githubusercontent.com/65744738/169934011-55acface-50c8-4c77-b022-8472cb2e6170.png)
<br>
Balanced Accuracy: 0.6443721269403855
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.63
Recall Low: 0.66

Undersampling
<br>
![Undersampling](https://user-images.githubusercontent.com/65744738/169934303-a81d4211-780f-4a1b-84a9-87c91ab7e169.png)
<br>
Balanced Accuracy: 0.6443721269403855
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.61
Recall Low: 0.45

Combination Over and Undersampling
<br>
![ComboOverUnder](https://user-images.githubusercontent.com/65744738/169934370-82c9781c-419c-49cf-a01a-8e72292f9660.png)
<br>
Balanced Accuracy: 0.5290690178920354
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.61
Recall Low: 0.45

Random Forest Classifiers
<br>
![BalencedRandomForestClassifiers](https://user-images.githubusercontent.com/65744738/169934396-5dbaae4c-4d08-430c-8577-c17a84abb99c.png)
<br>
Balanced Accuracy: 0.7877672625306695
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.67
Recall Low: 0.91

Easy Ensemble AdaBoosting:
<br>
![EasyEnsembleAdaBoost](https://user-images.githubusercontent.com/65744738/169934442-6720d441-2e94-4e9b-9bd1-7af3f436aa77.png)
<br>
Balanced Accuarcy: 0.925427358175101
Precision -> High Risk: Low, Low Risk: High.
Recall High: 0.91
Recall Low: 0.94


## Summary: 
Based on all the models the best to use is the Easy Ensemble Adaboost model. It has the highest Balenced accuracy score and the highest recall values for both High and Low risk clients. 
