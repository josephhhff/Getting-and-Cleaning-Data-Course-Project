The goals of this project are listed:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The run_analysis.R uses several variables, the general order of the variables are:

#Reading: train
x_train <- read.table
y_train <- read.table
subject_train <- read.table

#Reading: test
x_test <- read.table
y_test <- read.table
subject_test <- read.table

#Reading: feature vector
features <- read.table

#Reading: activity labels
activityLabels = read.table

#Setting: column names
colnames(x_train) <- features
colnames(y_train) <- ""
colnames(subject_train) <- ""

colnames(x_test) <- features
colnames(y_test) <- ""
colnames(subject_test) <- ""

colnames(activityLabels) <- c

#Merging: the sets in one dataset
mrg_train <- cbind
mrg_test <- cbind
setAllInOne <- rbind

##Extract only the measurements on the mean and standard deviation for each measurement
#Reading: column names
colNames <- colnames

#Creating vector: Id, mean and standard deviation
mean_and_std <- 

#Making: subset
setForMeanAndStd <-

##Use descriptive activity names to name the activities in the data set
setWithActivityNames <- merge

##Creating: a second, independent tidy data set with the average of each variable for each activity and each subject
secTidySet <- aggregate
secTidySet <- secTidySet

write.table
