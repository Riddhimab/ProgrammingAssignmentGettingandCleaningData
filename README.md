# ProgrammingAssignmentGettingandCleaningData
Getting and Cleaning Data Programming Assignment:

This repository was created to complete the assignment for the Getting and Cleaning Data Coursera course.

The first task is to download and unzip the data file into the R working directory.
The next task is to download the R source code into your R working directory.
The final task is to execute R source code to generate tidy data file.

Description of Data: 
 The variable in the data Y indicates the type of activity in which the  subjects performed during recording.
The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects.


Explanation and Working of the Code:

The code combines training dataset and test dataset, and helps extract partial variables to create another dataset with the averages of each variable for each activity.

The new dataset contained variables are calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

This Code:

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names.
5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
