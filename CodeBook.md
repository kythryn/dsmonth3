This is the code book for the file m3working.r

Running the file produces a table called tidydata.txt. This can be read back into r using read.table.

The tidy table contains information about the means and standard deviations for a number of measurements taken from the accelerometer of the Samsung Galaxy S smartphone.
The measurements concern the time, frequencey and various readings from the accelerometer. The codebook for the original data can be seen [here](https://github.com/kythryn/dsmonth3/tree/master/UCI%20HAR%20Dataset%202).




| Column                                | Name in data set           | Unit |
| --------------------------------------|:-------------:| -----|
| subject                               | -             | Number from 1 to 30 |
| activty                               | -             |  One of six factors: WALKING, WALKING DOWNSTAIRS, WALKING UPSTAIRS, SITTING, STANDING, LAYING |
| TimeBodyAcceleration-Mean-X           | tBodyAcc-mean()-X     |    g as a 128 element vector |
| TimeBodyAcceleration-Mean-Y           | tBodyAcc-mean()-Y      |    g as a 128 element vector |
| TimeBodyAcceleration-Mean-Z           | tBodyAcc-mean()-Z      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-X             | tBodyAcc-std()-X      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-Y             | tBodyAcc-std()-Y      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-Z             | tBodyAcc-std()-Z      |    g as a 128 element vector |
| TimeGravityAccelerationMean-X         | tGravityAcc-mean()-X       |    g as a 128 element vector |
| TimeGravityAccelerationMean-Y         | tGravityAcc-mean()-Y     |    g as a 128 element vector |
| TimeGravityAccelerationMean-Z         | tGravityAcc-mean()-Z       |    g as a 128 element vector |
| TimeGravityAccelerationSTD-X          | tGravityAcc-std()-X     |    g as a 128 element vector |
| TimeGravityAccelerationSTD-Y          | tGravityAcc-std()-Y      |    g as a 128 element vector |
| TimeGravityAccelerationSTD-Z          | tGravityAcc-std()-Z     |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-X        | tBodyAccJerk-mean()-X      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-Y        | tBodyAccJerk-mean()-Y      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-Z        | tBodyAccJerk-mean()-Z |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-X         | tBodyAccJerk-std()-X     |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-Y         | tBodyAccJerk-std()-Y     |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-Z         | tBodyAccJerk-std()-Z      |    g as a 128 element vector |
| TimeBodyGyroMean-X                    | tBodyGyro-mean()-X     |    g as a 128 element vector |
| TimeBodyGyroMean-Y                    | tBodyGyro-mean()-Y     |    g as a 128 element vector |
| TimeBodyGyroMean-Z                    | tBodyGyro-mean()-Z     |    g as a 128 element vector |
| TimeBodyGyroSTD-X                     | tBodyGyro-std()-X      |    g as a 128 element vector |
| TimeBodyGyroSTD-Y                     | tBodyGyro-std()-Y     |    g as a 128 element vector |
| TimeBodyGyroSTD-Z                     | tBodyGyro-std()-Z    |    g as a 128 element vector |
| TimeBodyGyroJerkMean-X                | tBodyGyroJerk-mean()-X     |    g as a 128 element vector |
| TimeBodyGyroJerkMean-Y                | tBodyGyroJerk-mean()-Y      |    g as a 128 element vector |
| TimeBodyGyroJerkMean-Z                | tBodyGyroJerk-mean()-Z     |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-X                 | tBodyGyroJerk-std()-X      |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-Y                 | tBodyGyroJerk-std()-Y     |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-Z                 | tBodyGyroJerk-std()-Z      |    g as a 128 element vector |
| TimeBodyAccelerationMagnitudeMean     | tBodyAccMag-mean()     |    g as a 128 element vector |
| TimeBodyAccelerationMagnitudeSTD      | tBodyAccMag-std()      |    g as a 128 element vector |
| TimeGravityAccelerationMagnitudeMean  | tGravityAccMag-mean()     |    g as a 128 element vector |
| TimeGravityAccelerationMagnitureSTD   | tGravityAccMag-std()     |    g as a 128 element vector |
| TimeBodyAccelerationJerkMagnitureMean | tBodyAccJerkMag-mean()      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMagnitureSTD  | tBodyAccJerkMag-std()      |    g as a 128 element vector |
| TimeBodyGyroMagnitureMean             | tBodyGyroMag-mean()      |    g as a 128 element vector |
| TimeBodyGyroMagnitureSTD              | tBodyGyroMag-std()     |    g as a 128 element vector |
| TimeBodyGyroJerkMagnitudeMean         | tBodyGyroJerkMag-mean()     |    g as a 128 element vector |
| TimeBodyGyroJerkMagnitudeSTD          | tBodyGyroJerkMag-std()     |    g as a 128 element vector |
| FreqBodyAcceleration-Mean-X           | fBodyAcc-mean()-X     |    g as a 128 element vector |
| FreqBodyAcceleration-Mean-Y           | fBodyAcc-mean()-Y     |    g as a 128 element vector |
| FreqBodyAccelerationMean-Z            | fBodyAcc-mean()-Z     |    g as a 128 element vector |
| FreqBodyAccelerationSTD-X             | fBodyAcc-std()-X     |    g as a 128 element vector |
| FreqBodyAccelerationSTD-Y             | fBodyAcc-std()-Y      |    g as a 128 element vector |
| FreqBodyAccerlationSTD-Z              | fBodyAcc-std()-Z      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-X        | fBodyAccJerk-mean()-X      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-Y        | fBodyAccJerk-mean()-Y      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-Z        | fBodyAccJerk-mean()-Z      |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-X         | fBodyAccJerk-std()-X      |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-Y         | fBodyAccJerk-std()-Y     |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-Z         | fBodyAccJerk-std()-Z     |    g as a 128 element vector |
| FreqBodyGyroMean-X                    | fBodyGyro-mean()-X     |    g as a 128 element vector |
| FreqBodyGyroMean-Y                    | fBodyGyro-mean()-Y    |    g as a 128 element vector |
| FreqBodyGyroMean-Z                    | fBodyGyro-mean()-Z     |    g as a 128 element vector |
| FreqBodyGyroSTD-X                     | fBodyGyro-std()-X      |    g as a 128 element vector |
| FreqBodyGyroSTD-Y                     | fBodyGyro-std()-Y      |    g as a 128 element vector |
| FreqBodyGyroSTD-Z                     | fBodyGyro-std()-Z     |    g as a 128 element vector |
| FreqBodyAccelerationMagnitudeMean     | fBodyAccMag-mean()     |    g as a 128 element vector |
| FreqBodyAccelerationMagnitudeSTD      | fBodyAccMag-std()      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMagnitureMean | fBodyBodyAccJerkMag-mean()     |    g as a 128 element vector |
| FreqBodyAccelerationJerkMagnitureSTD  | fBodyBodyAccJerkMag-std()      |    g as a 128 element vector |
| FreqBodyGyroMagnitureMean             | fBodyBodyGyroMag-mean()    |    g as a 128 element vector |
| FreqBodyGyroMagnitureSTD              | fBodyBodyGyroMag-std()      |    g as a 128 element vector |
| FreqBodyGyroJerkMagnitudeMean         | fBodyBodyGyroMag-std()     |    g as a 128 element vector |
| FreqBodyGyroJerkMagnitudeSTD          | fBodyBodyGyroMag-std()     |    g as a 128 element vector |

