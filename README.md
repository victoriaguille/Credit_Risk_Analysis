# Credit_Risk_Analysis
### Overview
####
With credit card risk being a historically difficult data type to assess with machine learning, this analysis takes the approach of six separate types of machine learning methods to assess the same data set. The testing of each model provides different methods to attempt acccurately predicting whether there is a high or low credit risk. In this particular data set on credit card credit from LendingClub, has an extremely low number of high risk applicants. This low number will lead to false positives when attempting to use a machine learning model on the data. In order to attempt to combat this, an analysis was performed using six separate models from oversampling to undersampling to random forests. 

### Results
####
Below are the results from the supervised learning models used on the loan data. 
- Naive Random Oversampling - 62% accuracy, 99% precision, 62% recall
- SMOTE Oversampling - 64% accuracy, 99% precision, 62% recall
- Cluster Centroids - 54% accuracy, 99% precision, 40% recall
- Smoteenn - 64% accuracy, 99% precision, 62% recall
- Balanced Random Forest - 79% accuracy, 99% precision, 87% recall
- Easy Ensemble AdaBoost - 93% accuracy, 99% precision, 94% recall

### Summary
####
as was expected, nearly all of the machine learning models had poor accuracy percentages and overfitting with 99% precision. oversampling of the high risk data did not aid in the training and testing of the models. the two closest models for potential success were the ensemble classifiers. of the two, the easy ensemble adaboost would be the most reliable machine learning model to use on credit risk data sets. had the highest accuracy at 93 and recall was only a point higher. so even if the precision might not be accurate, the judgement calls being made by the model are regularly identifying credit risks appropriately. this may not always work for other data sets, but in this particular situation it is useful. 
