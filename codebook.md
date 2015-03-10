{\rtf1\ansi\ansicpg936\cocoartf1265\cocoasubrtf210
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red38\green38\blue38;\red255\green255\blue255;\red38\green38\blue38;
}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}.}{\leveltext\leveltemplateid1\'02\'00.;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl500

\f0\fs24 \cf2 \cb3 This dataset is derived from the "Human Activity Recognition Using Smartphones Data Set\'94.\
\pard\pardeftab720\sl420
\cf0 Here are the data for the project: \
\pard\pardeftab720\sl420
{\field{\*\fldinst{HYPERLINK "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"}}{\fldrslt \cf0 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip}}\
\
\pard\tx566\pardeftab720\sl420\sa210
\cf2 Here are explanation about variables:\
\pard\pardeftab720\sl500
\cf2 Read X_train.txt, y_train.txt and subject_train.txt store in trainData, trainable and trainSubject.\
\pard\pardeftab720\sl500
\cf4 \cb1 Read X_test.txt, y_test.txt and subject_test.txt store in testData, testLable and testSubject.\
joinData = testData + trainDate.\
joinLabel = testLabel + trainLabel.\
joinSubject = testSubject + trainSubject.\
\pard\pardeftab720\sl500
\cf2 \cb3 features.txt store in feature\
activity_labels store in activity.\
cleanedData = joinSubject + joinLabel + joinData.\
\
\pard\pardeftab720\sl420
\cf0 \cb1 Here are the steps for this project:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl420
\ls1\ilvl0\cf4 {\listtext	1.	}Merges the training and the test sets to create one data set.\
{\listtext	2.	}Extracts only the measurements on the mean and standard deviation for each measurement.\'a0\
{\listtext	3.	}Uses descriptive activity names to name the activities in the data set\
{\listtext	4.	}Appropriately labels the data set with descriptive variable\'a0names.\'a0\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sl420\sa210
\ls1\ilvl0\cf4 {\listtext	5.	}From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.\
\pard\pardeftab720\sl500

\fs32 \cf2 \cb3 \

\fs24   \
}