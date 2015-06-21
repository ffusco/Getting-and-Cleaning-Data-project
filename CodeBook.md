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

##Description of the variables in the tiny_data.txt file
General description of the file including:
 - Dimensions of the dataset
 - Summary of the data
 - Variables present in the dataset

(you can easily use Rcode for this, just load the dataset and provide the information directly form the tidy data file)

###Variables
- "activityNumber" 
- "activityDescription" 
- "subjectNumber" 
- "tBodyAcc-mean()-X" 
- "tBodyAcc-mean()-Y" 
- "tBodyAcc-mean()-Z" 
- "tGravityAcc-mean()-X" 
- "tGravityAcc-mean()-Y" 
- "tGravityAcc-mean()-Z" 
- "tBodyAccJerk-mean()-X" 
- "tBodyAccJerk-mean()-Y" 
- "tBodyAccJerk-mean()-Z" 
- "tBodyGyro-mean()-X" 
- "tBodyGyro-mean()-Y" 
- "tBodyGyro-mean()-Z" 
- "tBodyGyroJerk-mean()-X" 
- "tBodyGyroJerk-mean()-Y" 
- "tBodyGyroJerk-mean()-Z" 
- "tBodyAccMag-mean()" 
- "tGravityAccMag-mean()" 
- "tBodyAccJerkMag-mean()" 
- "tBodyGyroMag-mean()" 
- "tBodyGyroJerkMag-mean()" 
- "fBodyAcc-mean()-X" 
- "fBodyAcc-mean()-Y" 
- "fBodyAcc-mean()-Z" 
- "fBodyAcc-meanFreq()-X" 
- "fBodyAcc-meanFreq()-Y" 
- "fBodyAcc-meanFreq()-Z" 
- "fBodyAccJerk-mean()-X" 
- "fBodyAccJerk-mean()-Y" 
- "fBodyAccJerk-mean()-Z" 
- "fBodyAccJerk-meanFreq()-X" 
- "fBodyAccJerk-meanFreq()-Y" 
- "fBodyAccJerk-meanFreq()-Z" 
- "fBodyGyro-mean()-X" 
- "fBodyGyro-mean()-Y" 
- "fBodyGyro-mean()-Z" 
- "fBodyGyro-meanFreq()-X" 
- "fBodyGyro-meanFreq()-Y" 
- "fBodyGyro-meanFreq()-Z" 
- "fBodyAccMag-mean()" 
- "fBodyAccMag-meanFreq()" 
- "fBodyBodyAccJerkMag-mean()" 
- "fBodyBodyAccJerkMag-meanFreq()" 
- "fBodyBodyGyroMag-mean()" 
- "fBodyBodyGyroMag-meanFreq()" 
- "fBodyBodyGyroJerkMag-mean()" 
- "fBodyBodyGyroJerkMag-meanFreq()" 
- "angle(tBodyAccMean,gravity)" 
- "angle(tBodyAccJerkMean),gravityMean)" 
- "angle(tBodyGyroMean,gravityMean)" 
- "angle(tBodyGyroJerkMean,gravityMean)" 
- "angle(X,gravityMean)" 
- "angle(Y,gravityMean)" 
- "angle(Z,gravityMean)" 
- "tBodyAcc-std()-X" 
- "tBodyAcc-std()-Y" 
- "tBodyAcc-std()-Z" 
- "tGravityAcc-std()-X" 
- "tGravityAcc-std()-Y" 
- "tGravityAcc-std()-Z" 
- "tBodyAccJerk-std()-X" 
- "tBodyAccJerk-std()-Y" 
- "tBodyAccJerk-std()-Z" 
- "tBodyGyro-std()-X" 
- "tBodyGyro-std()-Y" 
- "tBodyGyro-std()-Z" 
- "tBodyGyroJerk-std()-X" 
- "tBodyGyroJerk-std()-Y" 
- "tBodyGyroJerk-std()-Z" 
- "tBodyAccMag-std()" 
- "tGravityAccMag-std()" 
- "tBodyAccJerkMag-std()" 
- "tBodyGyroMag-std()" 
- "tBodyGyroJerkMag-std()" 
- "fBodyAcc-std()-X" 
- "fBodyAcc-std()-Y" 
- "fBodyAcc-std()-Z" 
- "fBodyAccJerk-std()-X" 
- "fBodyAccJerk-std()-Y" 
- "fBodyAccJerk-std()-Z" 
- "fBodyGyro-std()-X" 
- "fBodyGyro-std()-Y" 
- "fBodyGyro-std()-Z" 
- "fBodyAccMag-std()" 
- "fBodyBodyAccJerkMag-std()" 
- "fBodyBodyGyroMag-std()" 
- "fBodyBodyGyroJerkMag-std()"

