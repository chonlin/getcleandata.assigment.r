## Step1
Download and unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
## Step2
read into tables and the data located in "featers" and "activityLabels"
## Step3
Extract only the the mean and standard deviation for Feathers's measurement.
##Step4
read into tables and the data located in "trainX","trainY","trainS","testX","testY",and "testS"
##Step5
Merge(cbind) data subset "trainX" and "trainY" with the trainS; merge data subset "testX and testY with the testS to inlude the descriptive activity names
##Step6
Merge(rbind) the trainX and the testX sets to create one data set named "fData"
##Step7
label the activity column in data set fData with descriptive activity names.
##Step8
Use package reshape2
##Step9
Use melt and dcast command to create "fData.final" data set with the average of each variable for each activity and each subject.
##Step10
creates a second, independent tidy 
"tidydata.txt"
