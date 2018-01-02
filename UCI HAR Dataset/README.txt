===================================================================================================
Human Activity Recognition Using Smartphones Dataset
==================================================================================
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
 Features are normalized and bounded within [-1,1].
 Each feature vector is a row on the text file.
 The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).
 The gyroscope units are rad/seg.
==================================================================================
Dataset Link:-http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

IDE :- Python3.5, Jupyter Notebook

Libraries Used:- Pandas,Numpy,Sklearn.

Used Linear SVC and filtered the useless features and selected the best 106 features from 563 which contributed the most for label.The accuracy obtained by using SVC classifier = 92.84%

Used Gradient Boosting Classifier and with grid search done parameter tuning and selected the parameter having maximum mean value.The accuracy obtained by using GBM Classifier = 93.99%

