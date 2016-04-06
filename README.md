# Getting-and-Cleaning-Data-Project

## Original Datasets
The features selected for this database is a recording of six different activity movements by smartphones of 30 subjects from the [site:](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).  The datasets are available [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Tasks Performed
The R script, run_analysis.R, performs the following tasks:
1.	Download and unzip the dataset if it does not already exist in the working directory.
2.	Loads the activity, subject, and feature files.
3.	Merges the original training and the test sets to create one data set.
4.	Extracts only the measurements on the mean and standard deviation for each measurement.
5.	Uses descriptive activity names to name the activities in the data set
6.	Appropriately labels the data set with descriptive variable names.
7.	From the data set in step 4, creates a second, independent tidy data (tidydata.txt) set with the average of each variable for each activity and each subject.

