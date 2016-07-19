Code Book
=========

This code book summarizes the resulting data fields in MeanData.txt.

Identifiers
===========

subject - The ID of the test subject
activity - The type of activity performed when the corresponding measurements were taken

Feature Selection 
=================

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

Measurements
================


[1] "subject"                          "activity"                         "timeBodyAccMean-X"                "timeBodyAccMean-Y"      [5] "timeBodyAccMean-Z"                "timeBodyAccStd-X"                 "timeBodyAccStd-Y"                 "timeBodyAccStd-Z"     [9] "timeGravityAccMean-X"             "timeGravityAccMean-Y"             "timeGravityAccMean-Z"             "timeGravityAccStd-X"    [13] "timeGravityAccStd-Y"              "timeGravityAccStd-Z"              "timeBodyAccJerkMean-X"            "timeBodyAccJerkMean-Y" [17] "timeBodyAccJerkMean-Z"            "timeBodyAccJerkStd-X"             "timeBodyAccJerkStd-Y"             "timeBodyAccJerkStd-Z"
[21] "timeBodyGyroMean-X"               "timeBodyGyroMean-Y"               "timeBodyGyroMean-Z"               "timeBodyGyroStd-X"     [25] "timeBodyGyroStd-Y"                "timeBodyGyroStd-Z"                "timeBodyGyroJerkMean-X"           "timeBodyGyroJerkMean-Y"
[29] "timeBodyGyroJerkMean-Z"           "timeBodyGyroJerkStd-X"            "timeBodyGyroJerkStd-Y"            "timeBodyGyroJerkStd-Z" [33] "timeBodyAccMagMean"               "timeBodyAccMagStd"                "timeGravityAccMagMean"            "timeGravityAccMagStd"  [37] "timeBodyAccJerkMagMean"           "timeBodyAccJerkMagStd"            "timeBodyGyroMagMean"              "timeBodyGyroMagStd"    [41] "timeBodyGyroJerkMagMean"          "timeBodyGyroJerkMagStd"           "frequenceBodyAccMean-X"           "frequenceBodyAccMean-Y"
[45] "frequenceBodyAccMean-Z"           "frequenceBodyAccStd-X"            "frequenceBodyAccStd-Y"            "frequenceBodyAccStd-Z" [49] "frequenceBodyAccJerkMean-X"       "frequenceBodyAccJerkMean-Y"       "frequenceBodyAccJerkMean-Z"   "frequenceBodyAccJerkStd-X" [53] "frequenceBodyAccJerkStd-Y"        "frequenceBodyAccJerkStd-Z"        "frequenceBodyGyroMean-X"        "frequenceBodyGyroMean-Y" [57] "frequenceBodyGyroMean-Z"          "frequenceBodyGyroStd-X"           "frequenceBodyGyroStd-Y"           "frequenceBodyGyroStd-Z"
[61] "frequenceBodyAccMagMean"          "frequenceBodyAccMagStd"           "frequenceBodyBodyAccJerkMagMean"
"frequenceBodyBodyAccJerkMagStd"  
[65] "frequenceBodyBodyGyroMagMean"     "frequenceBodyBodyGyroMagStd"      "frequenceBodyBodyGyroJerkMagMean" "frequenceBodyBodyGyroJerkMagStd" 

Activity Labels
=================

WALKING (value 1): subject was walking during the test
WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
SITTING (value 4): subject was sitting during the test
STANDING (value 5): subject was standing during the test
LAYING (value 6): subject was laying down during the test
