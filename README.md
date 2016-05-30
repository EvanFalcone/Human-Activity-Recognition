# Intro

run_analysis.R script reads data from the UCI HAR Data set and outputs a tidy data set for further analytical use.
The data was acquired via experiments carried out with a group of 30 volunteers within the ages of 19-48 years.

Six activities were performed (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing 
a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear 
acceleration and 3-axial angular velocity at a constant rate of 50Hz.

The dataset was randomly divided into two sets - 70% of the volunteers was selected for the training data and 30%,
the test data. 

# Original Data Set Features

    'features.txt': List of all features.

    'activity_labels.txt': List of class labels and their activity name.

    'train/X_train.txt': Training set.

    'train/y_train.txt': Training labels.

    'train/subject_train.txt': ID's of subjects in the training data
 
    'test/X_test.txt': Test set.

    'test/y_test.txt': Test labels.

    'test/subject_test.txt': ID's of subjects in the training data

# run_analysis. R Script

The run_analysis.R script merges data from a number of .txt files and produces a tidy data set which may be used for
further analysis.

A description of the "tidy_movement_data.txt" file may be found in the "CodeBook.md" file. 

    'test/X_test.txt': Test set.

    'test/y_test.txt': Test labels.

    'test/subject_test.txt': ID's of subjects in the training data
