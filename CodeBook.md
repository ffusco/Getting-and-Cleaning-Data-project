---
title: "Codebook template"
author: "Fabio Fusco"
date: "2015/06/20"
---

## Project Description
Preparing tidy data that can be used for later analysis.

###Collection of the raw data
The data was collected from this site:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Original description of the dataset: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The dataset includes the following files:

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent.

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.

##Creating the tidy datafile

###Guide to create the tidy data file
The script is available here:
https://github.com/ffusco/Getting-and-Cleaning-Data-project/blob/master/run_analysis.R

The description of the procedure is here:
https://github.com/ffusco/Getting-and-Cleaning-Data-project/blob/master/README.md

##Description of tinyData.txt file
- 286 KB
- 180 observations of 89 variables.

###Variables
For the complete description of all the variables please refer to the file "features_info.txt" of the dataset.


- "activityNumber": integer between 1 and 6  
- "activityDescription": factor, 6 levels: WALKING - WALKING_UPSTAIRS - WALKING_DOWNSTAIRS - SITTING - STANDING - LAYING
- "subjectNumber": integer between 1 and 30 indicating the subject   
- "tBodyAcc-mean()-X": numeric between -1 and 1 
- "tBodyAcc-mean()-Y": numeric between -1 and 1 
- "tBodyAcc-mean()-Z" : numeric between -1 and 1
- "tGravityAcc-mean()-X": numeric between -1 and 1
- "tGravityAcc-mean()-Y": numeric between -1 and 1
- "tGravityAcc-mean()-Z": numeric between -1 and 1 
- "tBodyAccJerk-mean()-X": numeric between -1 and 1 
- "tBodyAccJerk-mean()-Y": numeric between -1 and 1 
- "tBodyAccJerk-mean()-Z": numeric between -1 and 1 
- "tBodyGyro-mean()-X": numeric between -1 and 1 
- "tBodyGyro-mean()-Y": numeric between -1 and 1 
- "tBodyGyro-mean()-Z": numeric between -1 and 1 
- "tBodyGyroJerk-mean()-X": numeric between -1 and 1 
- "tBodyGyroJerk-mean()-Y": numeric between -1 and 1 
- "tBodyGyroJerk-mean()-Z": numeric between -1 and 1 
- "tBodyAccMag-mean()": numeric between -1 and 1 
- "tGravityAccMag-mean()": numeric between -1 and 1 
- "tBodyAccJerkMag-mean()": numeric between -1 and 1 
- "tBodyGyroMag-mean()": numeric between -1 and 1 
- "tBodyGyroJerkMag-mean()": numeric between -1 and 1 
- "fBodyAcc-mean()-X": numeric between -1 and 1 
- "fBodyAcc-mean()-Y": numeric between -1 and 1 
- "fBodyAcc-mean()-Z": numeric between -1 and 1 
- "fBodyAcc-meanFreq()-X": numeric between -1 and 1 
- "fBodyAcc-meanFreq()-Y": numeric between -1 and 1 
- "fBodyAcc-meanFreq()-Z": numeric between -1 and 1 
- "fBodyAccJerk-mean()-X": numeric between -1 and 1 
- "fBodyAccJerk-mean()-Y": numeric between -1 and 1 
- "fBodyAccJerk-mean()-Z": numeric between -1 and 1 
- "fBodyAccJerk-meanFreq()-X": numeric between -1 and 1 
- "fBodyAccJerk-meanFreq()-Y": numeric between -1 and 1 
- "fBodyAccJerk-meanFreq()-Z": numeric between -1 and 1 
- "fBodyGyro-mean()-X": numeric between -1 and 1 
- "fBodyGyro-mean()-Y": numeric between -1 and 1 
- "fBodyGyro-mean()-Z": numeric between -1 and 1 
- "fBodyGyro-meanFreq()-X": numeric between -1 and 1 
- "fBodyGyro-meanFreq()-Y": numeric between -1 and 1 
- "fBodyGyro-meanFreq()-Z": numeric between -1 and 1 
- "fBodyAccMag-mean()": numeric between -1 and 1 
- "fBodyAccMag-meanFreq()": numeric between -1 and 1 
- "fBodyBodyAccJerkMag-mean()": numeric between -1 and 1 
- "fBodyBodyAccJerkMag-meanFreq()": numeric between -1 and 1 
- "fBodyBodyGyroMag-mean()": numeric between -1 and 1 
- "fBodyBodyGyroMag-meanFreq()": numeric between -1 and 1 
- "fBodyBodyGyroJerkMag-mean()": numeric between -1 and 1 
- "fBodyBodyGyroJerkMag-meanFreq()": numeric between -1 and 1 
- "angle(tBodyAccMean,gravity)": numeric between -1 and 1 
- "angle(tBodyAccJerkMean),gravityMean)": numeric between -1 and 1 
- "angle(tBodyGyroMean,gravityMean)": numeric between -1 and 1 
- "angle(tBodyGyroJerkMean,gravityMean)": numeric between -1 and 1 
- "angle(X,gravityMean)": numeric between -1 and 1 
- "angle(Y,gravityMean)": numeric between -1 and 1 
- "angle(Z,gravityMean)": numeric between -1 and 1 
- "tBodyAcc-std()-X": numeric between -1 and 1 
- "tBodyAcc-std()-Y": numeric between -1 and 1 
- "tBodyAcc-std()-Z": numeric between -1 and 1 
- "tGravityAcc-std()-X": numeric between -1 and 1 
- "tGravityAcc-std()-Y": numeric between -1 and 1 
- "tGravityAcc-std()-Z": numeric between -1 and 1 
- "tBodyAccJerk-std()-X": numeric between -1 and 1 
- "tBodyAccJerk-std()-Y": numeric between -1 and 1 
- "tBodyAccJerk-std()-Z": numeric between -1 and 1 
- "tBodyGyro-std()-X": numeric between -1 and 1 
- "tBodyGyro-std()-Y": numeric between -1 and 1 
- "tBodyGyro-std()-Z": numeric between -1 and 1 
- "tBodyGyroJerk-std()-X": numeric between -1 and 1 
- "tBodyGyroJerk-std()-Y": numeric between -1 and 1 
- "tBodyGyroJerk-std()-Z": numeric between -1 and 1 
- "tBodyAccMag-std()": numeric between -1 and 1 
- "tGravityAccMag-std()": numeric between -1 and 1 
- "tBodyAccJerkMag-std()": numeric between -1 and 1 
- "tBodyGyroMag-std()": numeric between -1 and 1 
- "tBodyGyroJerkMag-std()": numeric between -1 and 1 
- "fBodyAcc-std()-X": numeric between -1 and 1 
- "fBodyAcc-std()-Y": numeric between -1 and 1 
- "fBodyAcc-std()-Z"v 
- "fBodyAccJerk-std()-X": numeric between -1 and 1 
- "fBodyAccJerk-std()-Y": numeric between -1 and 1 
- "fBodyAccJerk-std()-Z": numeric between -1 and 1 
- "fBodyGyro-std()-X": numeric between -1 and 1 
- "fBodyGyro-std()-Y": numeric between -1 and 1 
- "fBodyGyro-std()-Z": numeric between -1 and 1 
- "fBodyAccMag-std()": numeric between -1 and 1 
- "fBodyBodyAccJerkMag-std()": numeric between -1 and 1 
- "fBodyBodyGyroMag-std()": numeric between -1 and 1 
- "fBodyBodyGyroJerkMag-std()": numeric between -1 and 1

