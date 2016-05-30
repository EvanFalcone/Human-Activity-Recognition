# Human-Activity-Recognition
Getting and Cleaning Data Course Project - Human Activity Recognition

# Features:
The features chosen for this data set came from the data in the "Human Activity Recognition Using Smartphones Dataset Version 1.0": Taken from experiments carried out with 30 volunteers within the ages of 19-48 years. Each person performed 6 activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) strapped to them. Using its accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz data were captured, of accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.

These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tBodyAcc-XYZ tGravityAcc-XYZ tBodyAccJerk-XYZ tBodyGyro-XYZ tBodyGyroJerk-XYZ tBodyAccMag tGravityAccMag tBodyAccJerkMag tBodyGyroMag tBodyGyroJerkMag fBodyAcc-XYZ fBodyAccJerk-XYZ fBodyGyro-XYZ fBodyAccMag fBodyAccJerkMag fBodyGyroMag fBodyGyroJerkMag

angle(): Angle between two vectors.

Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:

gravityMean tBodyAccMean tBodyAccJerkMean tBodyGyroMean tBodyGyroJerkMean

# Feature Vector vars:
mean() : mean values of multiple measurements of the original variables. Type: Real number

std(): Standard deviation of multiple measurements of the original variables. Type: Real number

activity_id: Identifier, identifying the activity of each subject Type: Integer Values: 1 : 6

activity_name: Descriptive name of each subject's activity Type: Factor Values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

subject_id : Identifier, identifying each subject Type: Integer Values: 1 : 30
