### README

#### Getting and Cleaning Data Course Project: Peer-graded Assignment

The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.  

I will be graded by my peers on a series of yes/no questions related to the project. I will be required to submit: 
* 1) a tidy data set as described below, 
* 2) a link to a Github repository with your script for performing the analysis, and 
* 3) a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data called CodeBook.md.

This repo explains how all of the scripts work and how they are connected.


#### Dataset

[Human Activity Recognition Using Smartphones Data Set](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)


#### Files

* `CodeBook.md` a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

* `run_analysis.R` performs the data preparation and then followed by the 5 steps required as described in the course project's definition:
    + Merges the training and the test sets to create one data set.
    + Extracts only the measurements on the mean and standard deviation for each measurement.
    + Uses descriptive activity names to name the activities in the data set
    + Appropriately labels the data set with descriptive variable names.
    + From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
    
* `FinalData.txt` is the exported final data after going through all the sequences described above.
