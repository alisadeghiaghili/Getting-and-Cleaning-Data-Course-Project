# Getting and Cleaning Data Course by Johns Hopkins University
#### Final Project

This repository is a **Seyed Ali Sadeghi Aghili**'s submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset. 

*__Notice__: __In some parts of this project other functions like bind_rows, bind_cols and rename could be used instead of rbidn, cbind and gsub. But as the matter of Peer assesment I used simple functions.__*

## Dataset
Human Activity Recognition Using Smartphones

## Files

  * __`CodeBook.md`__ a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data
  * __`Getting And Cleaning Data.R`__ performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
    * Merges the training and the test sets to create one data set.
    * Extracts only the measurements on the mean and standard deviation for each measurement.
    * Uses descriptive activity names to name the activities in the data set
    * Appropriately labels the data set with descriptive variable names.
    * From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  * __`Result.txt`__ is the exported final data after going through all the sequences described above
