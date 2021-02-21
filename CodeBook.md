---
title: "CodeBook"
author: "TF"
date: "2021/2/20"
output: html_document
---

### ave_by

This means how the average of other variables were calculated.  
There are 2 cases.  

1. The case where the variable is Specified by 3 capital letters.  
For example: DOW  
This means the average of 30 subjects who performed *WALKING_DOWNSTAIRS* activity.

How 3 capital letters corresponds to the activity is shown as follows.

- WAL -> WALKING  
- UPS -> WALKING_UPSTAIRS  
- DOW -> WALKING_DOWNSTAIRS  
- SIT -> SITTING  
- STA -> STANDING  
- LAY -> LAYING  
  
2. The case where the variable is specified by the integer number from 1 to 30.  

Each integer number means the average of 6 activities which were performed by each subject.  



### tBAmX
This means the average of ***tBodyAcc-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  


### tBAmY
This means the average of ***tBodyAcc-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tBAmZ
This means the average of ***tBodyAcc-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tBAsX
This means the average of ***tBodyAcc-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tBAsY
This means the average of ***tBodyAcc-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tBAsZ
This means the average of ***tBodyAcc-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tGrAmX
This means the average of ***tGravityAcc-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].  

### tGrAmY
This means the average of ***tGravityAcc-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAmZ
This means the average of ***tGravityAcc-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAsX
This means the average of ***tGravityAcc-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAsY
This means the average of ***tGravityAcc-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAsZ
This means the average of ***tGravityAcc-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJmX
This means the average of ***tBodyAccJerk-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJmY
This means the average of ***tBodyAccJerk-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJmZ
This means the average of ***tBodyAccJerk-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJsX
This means the average of ***tBodyAccJerk-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJsY
This means the average of ***tBodyAccJerk-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJsZ
This means the average of ***tBodyAccJerk-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGymX
This means the average of ***tBodyGyro-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGymY
This means the average of ***tBodyGyro-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGymZ
This means the average of ***tBodyGyro-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGysX
This means the average of ***tBodyGyro-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGysY
This means the average of ***tBodyGyro-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGysZ
This means the average of ***tBodyGyro-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJmX
This means the average of ***tBodyGyroJerk-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJmY
This means the average of ***tBodyGyroJerk-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJmZ
This means the average of ***tBodyGyroJerk-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJsX
This means the average of ***tBodyGyroJerk-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJsY
This means the average of ***tBodyGyroJerk-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJsZ
This means the average of ***tBodyGyroJerk-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAMm
This means the average of ***tBodyAccMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAMs
This means the average of ***tBodyAccMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAMm
This means the average of ***tGravityAccMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tGrAMs
This means the average of ***tGravityAccMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJMm
This means the average of ***tBodyAccJerkMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBAJMs
This means the average of ***tBodyAccJerkMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyMm
This means the average of ***tBodyGyroMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyMs
This means the average of ***tBodyGyroMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJMm
This means the average of ***tBodyGyroJerkMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### tBGyJMs
This means the average of ***tBodyGyroJerkMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAmX
This means the average of ***fBodyAcc-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAmY
This means the average of ***fBodyAcc-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAmZ
This means the average of ***fBodyAcc-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAsX
This means the average of ***fBodyAcc-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAsY
This means the average of ***fBodyAcc-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAsZ
This means the average of ***fBodyAcc-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJmX
This means the average of ***fBodyAccJerk-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJmY
This means the average of ***fBodyAccJerk-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJmZ
This means the average of ***fBodyAccJerk-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJsX
This means the average of ***fBodyAccJerk-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJsY
This means the average of ***fBodyAccJerk-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAJsZ
This means the average of ***fBodyAccJerk-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGymX
This means the average of ***fBodyGyro-mean()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGymY
This means the average of ***fBodyGyro-mean()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGymZ
This means the average of ***fBodyGyro-mean()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGysX
This means the average of ***fBodyGyro-std()-X***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGysY
This means the average of ***fBodyGyro-std()-Y***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBGysZ
This means the average of ***fBodyGyro-std()-Z***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAMm
This means the average of ***fBodyAccMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBAMs
This means the average of ***fBodyAccMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBAJMm
This means the average of ***fBodyBodyAccJerkMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBAJMs
This means the average of ***fBodyBodyAccJerkMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBGyMm
This means the average of ***fBodyBodyGyroMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBGyMs
This means the average of ***fBodyBodyGyroMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBGyJMm
This means the average of ***fBodyBodyGyroJerkMag-mean()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

### fBBGyJMs
This means the average of ***fBodyBodyGyroJerkMag-std()***.  
The detail definition of this variable is shown in **features_info.txt** in UCI HAR Dataset.    
How this average was calculated is specified by **ave_by**.  
Features are normalized and bounded within [-1,1].   

