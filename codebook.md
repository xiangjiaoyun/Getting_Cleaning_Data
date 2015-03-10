This dataset is derived from the "Human Activity Recognition Using Smartphones Data Set”.
Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Here are explanation about variables:
Read X_train.txt, y_train.txt and subject_train.txt store in trainData, trainable and trainSubject.

Read X_test.txt, y_test.txt and subject_test.txt store in testData, testLable and testSubject.

joinData = testData + trainDate.

joinLabel = testLabel + trainLabel.

joinSubject = testSubject + trainSubject.

features.txt store in feature.

activity_labels store in activity.

cleanedData = joinSubject + joinLabel + joinData.


Here are the steps for this project:
	Merges the training and the test sets to create one data set.
	
	Extracts only the measurements on the mean and standard deviation for each measurement. 
	
	Uses descriptive activity names to name the activities in the data set.
	
	Appropriately labels the data set with descriptive variable names. 
	
	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

