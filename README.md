# Credit_Risk_Analysis
### Overview
####
With credit card risk being a historically difficult data type to assess with machine learning, this analysis takes the approach of six separate types of machine learning methods to assess the same data set. The testing of each model provides different methods to attempt acccurately predicting whether there is a high or low credit risk. In this particular data set on credit card credit from LendingClub, has an extremely low number of high risk applicants. This low number will lead to false positives when attempting to use a machine learning model on the data. In order to attempt to combat this, an analysis was performed using six separate models from oversampling to undersampling to random forests. 

### Results
####
Below are the results from the supervised learning models used on the credit risk data set and the percentages for accuracy, precision, and recall of each model type.  
- Naive Random Oversampling - 62% accuracy, 99% precision, 62% recall
####
![naive](link)
####
- SMOTE Oversampling - 64% accuracy, 99% precision, 62% recall
####
![smote](link)
####
- Cluster Centroids - 54% accuracy, 99% precision, 40% recall
####
![cluster](link)
####
- Smoteenn - 64% accuracy, 99% precision, 62% recall
####
![smoteenn](link)
####
- Balanced Random Forest - 79% accuracy, 99% precision, 87% recall
####
![brf](link)
####
- Easy Ensemble AdaBoost - 93% accuracy, 99% precision, 94% recall
####
![eec](link)

### Summary
####
Before beginning the modeling, there was little expectation for great success with how significant in variance there was between low risk and high risk data entries. As was expected, nearly all of the machine learning models had poor accuracy percentages and overfitting with 99% precision for every model. Oversampling of the high risk data did not aid in the traning and testing of the models as they had the lowest levels of accuracy and recall, with the least successful model being the cluster centroids method. The two closest models for potential success were the ensemble classifiers, the balanced random forest method and the easy ensemble adaboost method.These two methods would be the most reliable machine learning model to use on credit risk data sets based on the higher accuracy and recall scores. The precision scores stayed consistent at 99%. The easy ensemble model, with the accuracy score at 93% and recall score at 94%, was the most useful for correctly labeling high or low credit risks within the LendingClub data set. This particular model may not always work for other data sets, but in this particular situation, it is extremely useful.

