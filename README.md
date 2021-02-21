---
title: "README"
author: "TF"
date: "2021/2/20"
output: html_document
---

## How the script works

Using **UCI HAR Dataset**, this script (**run_analysis.R**) works as follows.  

1. Merges the training and the test sets to create one data set.  

2. Extracts only the measurements on the mean and standard deviation for each measurement.  

3. Uses descriptive activity names to name the activities in the data set.  

4. Appropriately labels the data set with descriptive variable names.  

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.  

As a result of above step 5, the output file  is created as **submission.txt**.  
This is the tidy data and the variables in it are explained in **CodeBook.md**.  

