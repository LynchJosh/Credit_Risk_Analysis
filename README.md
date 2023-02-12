# Credit_Risk_Analysis



#	Overview 
This project uses multiple machine learning techniques to help predict credit risk.  

- Balanced accuracy score is a metric that computes the average of recall scores of each class, with equal weight given to each class. It is used to evaluate classifier performance on imbalanced datasets.
- High risk vs low risk refers to the accuracy of positive predictions. It is the number of true positive predictions (correctly identified high risk instances) divided by the sum of true positive and false positive predictions (all instances predicted as high risk, whether they are actually high risk or not). High precision means that a large proportion of positive predictions are actually correct.
- Recall score is a measure of the completeness of a classifier's predictions. It is defined as the number of true positive predictions (correctly identified high risk instances) divided by the sum of true positive and false negative predictions (all actual high risk instances, whether they were correctly identified or not). 


#	Results

##	Naive Random Oversampling
Balanced Accuracy Score: (67%)
Precision: High Risk (1%) Low Risk (100%)
Recall: High Risk (57%) Low Risk (64%) 

![Naive Random Oversampling 1](https://user-images.githubusercontent.com/112728628/218329188-5af20524-693a-4b2e-aa06-e27fdcd3ba51.PNG)

##	SMOTE Oversampling
Balanced Accuracy Score: (66%)
Precision: High Risk (1%) Low Risk (100%)
Recall: High Risk (63%) Low Risk (69%) 

![SMOTE Oversampling 2](https://user-images.githubusercontent.com/112728628/218329192-3298a769-4def-46bf-bf1b-4c34ddb230ec.PNG)

##	Undersampling Using Cluster Centroids
Balanced Accuracy Score: (54%)
Precision: High Risk (1%) Low Risk (100%)
Recall: High Risk (69%) Low Risk (40%) 

![Undersampling Using Cluster Centroids 3](https://user-images.githubusercontent.com/112728628/218329200-7fb9179e-b084-48cc-89bf-6efec81269e3.PNG)

##	Over and Undersampling using SMOTEENN
Balanced Accuracy Score: (67%)
Precision: High Risk (1%) Low Risk (100%)
Recall: High Risk (75%) Low Risk (60%) 

![Over and Undersampling using SMOTEENN 4](https://user-images.githubusercontent.com/112728628/218329205-7406b087-449b-4a3b-a3f5-b565df078f35.PNG)

##	Balanced Random Forest Classifier
Balanced Accuracy Score: (79%)
Precision: High Risk (3%) Low Risk (100%)
Recall: High Risk (70%) Low Risk (87%) 

![Balanced Random Forest Classifier 5](https://user-images.githubusercontent.com/112728628/218329215-fbd774d6-3de8-41b9-b1d7-6b0b72d71620.PNG)

##	Easy Ensemble AdaBoost Classifier
Balanced Accuracy Score: (92%)
Precision: High Risk (5%) Low Risk (100%)
Recall: High Risk (93%) Low Risk (90%)

![Easy Ensemble AdaBoost Classifier 6](https://user-images.githubusercontent.com/112728628/218329220-862083eb-f53d-4a04-ac4d-d9a071ded345.PNG)

#	Summary
In this dataset, the ensemble learners outperformed the undersampling, oversampling, and combination models. It is recommended to use the Easy Ensemble Classifier as it excelled in all the metrics and demonstrated remarkable superiority in the majority of the categories.
