# classification_hw

## Resampling

### Which model had the best balanced accuracy score? The SMOTE Oversampling model has the highest balanced accuracy score.
#### Model accuracy score represents the model’s ability to correctly predict both the positives and negatives out of all the predictions. Mathematically, it represents the ratio of sum of true positive and true negatives out of all the predictions.
#### Random Oversampling = 0.832868
#### SMOTE Oversampling = 0.838851
#### ClusterCentroids Undersampling = 0.821557
#### SMOTEENN = 0.838831
### Which model had the best recall score? THe SMOTE Oversampling model has the highest recall score.
#### Model recall score represents the model’s ability to correctly predict the positives out of actual positives. This is unlike precision which measures as to how many predictions made by models are actually positive out of all positive predictions made. Recall score is a useful measure of success of prediction when the classes are very imbalanced.  Mathematically, it represents the ratio of true positive to the sum of true positive and false negative.
#### Random Oversampling = 0.84
#### SMOTE Oversampling = 0.87
#### ClusterCentroids Undersampling = 0.76
#### SMOTEENN = 0.86
### Which model had the best geometric mean score? The Smote Overampling and SMOTEENN have the highest geometric mean score of 0.84.
#### Random Oversampling = 0.83
#### SMOTE Oversampling = 0.84
#### ClusterCentroids Undersampling = 0.82
#### SMOTEENN = 0.84

## Ensemble Learning

### Which model had the best balanced accuracy score? The Easy Ensemble Classifier has a higher balanced accuracy score (0.931601)
#### Random Forest 0.788751
#### Easy Ensemble 0.931601
### Which model had the best recall score?
#### Random Forest 0.87
#### Easy Ensemble 0.94
### Which model had the best geometric mean score?
#### Random Forest 0.87
#### Easy Ensemble 0.78
### What are the top three features? See below
#### total_rec_prncp: 0.07876809003486353
#### total_pymnt: 0.05883806887524815
#### total_pymnt_inv: 0.05625613759225244