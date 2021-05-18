# PLANT
Given a dataset consisting features of leaves, classify these leaves into a multi class problem
### Methodology
- There are three features for each image: Shape, Margin and Texture. For each feature, a 64 element vector is given per leaf sample. These vectors are taken as a contiguous descriptor (for shape) or histograms (for texture and margin). Each row has a 64-element feature vector followed by the target variable Class label and it's value lies in the range 1-100 for 100 plants species.
- Trained model using an ensemble of classifiers - RandomForestClassifier, GradientBoostingClassifier
- Achieved an F1 score of 0.856 on test data

# LIGHT
Predict the class of the LED bulb
### Methodology
- The database contains various attributes about LED lights which are classified into 10 different types of classes from 0 to 9. All the attributes are nominal types and all have 2 unique values 0 or 1. There are in total 25 attributes out of which 24 are the nominal 0 or 1 types and the last one is the class of the lED light.
- Trained model using an ensemble of classifiers
- Achieved an F1 score of 0.742 on test data

# RECID
Predict whether the indiviual will be back to prison in the three year period or not
### Methodology
- Dataset contains information of criminal history, jail and prison time, demographics and COMPAS risk scores for defendants from Broward County. For each individual there are 14 variables including the target variable. The target variable is two_year_recid which indicates recidivism.
- Trained model using a voting classifier with RandomForestClassifier, GradientBoostingClassifier, LinearDiscriminantAnalysis, LinearSVC, LogisticRegression
- Achieved an F1 score of 0.676 on test data




