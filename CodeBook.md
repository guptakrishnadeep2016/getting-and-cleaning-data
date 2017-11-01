About source data

As sourse data for work was used Human Activity Recognition Using Smartphones Data Set. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

About R script

File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

Merging the training and the test sets to create one data set.
A>Reading files
1 Reading trainings tables
2 Reading testing tables
3 Reading feature vector
4 Reading activity labels
B>Assigning column names
1 Merging all data in one set
Extracting only the measurements on the mean and standard deviation for each measurement
A> Reading column names
B> Create vector for defining ID, mean and standard deviation
C> Making nessesary subset from setAllInOne
Using descriptive activity names to name the activities in the data set
Appropriately labeling the data set with descriptive variable names
Creating a second, independent tidy data set with the average of each variable for each activity and each subject
A> Making second tidy data set
B> Writing second tidy data set in txt file

Variables used:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names
