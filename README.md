Getting and Cleaning Data Course Project

You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

This file describes how run_analysis.R script works.

1.Unzip the data and rename the folder with "data".
Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
2. Run source("run_analysis.R") in RStudio.
3. Two output files are generated in the current working directory:
merged_data.txt : it contains a data frame called cleanedData.
data_with_means.txt : it contains a data frame called result.



