# Asteroid-classification
The main objective is to build a model that can be applied to classify hazardous asteroid. 

From the 39 columns (excluding target column) we find the best features that can explain whether the astroids are harmful or not
The freatures are:

['Absolute Magnitude'

'Minimum Orbit Intersection'

'Jupiter Tisserand Invariant'

'Eccentricity'


Best model was selected as stack model with estimator random forest and final estimaor as naive bayes with accuracy 99.36% and roc auc score 99.914%


