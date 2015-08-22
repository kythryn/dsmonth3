This is the code book for the file m3working.r

Running the file produces a table called tidydata.txt. This can be read back into r using read.table.

The tidy table contains information about the means and standard deviations for a number of measurements taken from the accelerometer of the Samsung Galaxy S smartphone.
The measurements concern the time, frequencey and various readings from the accelerometer. The codebook for the original data can be seen here.

Units of g as a 128 element vector



| Column                                | Name in data set           | Unit |
| --------------------------------------|:-------------:| -----|
| Subject                               | -             | Number from 1 to 30 |
| Activty                               | -             |  One of six factors: WALKING, WALKING DOWNSTAIRS, WALKING UPSTAIRS, SITTING, STANDING LAYING |
| TimeBodyAcceleration-Mean-X           | are neat      |    g as a 128 element vector |
| TimeBodyAcceleration-Mean-Y           | are neat      |    g as a 128 element vector |
| TimeBodyAcceleration-Mean-Z           | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-X             | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-Y             | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationSTD-Z             | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationMean-X         | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationMean-Y         | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationMean-Z         | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationSTD-X          | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationSTD-Y          | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationSTD-Z          | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-X        | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-Y        | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMean-Z        | right-aligned |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-X         | centered      |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-Y         | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkSTD-Z         | are neat      |    g as a 128 element vector |
| TimeBodyGyroMean-X                    | are neat      |    g as a 128 element vector |
| TimeBodyGyroMean-Y                    | are neat      |    g as a 128 element vector |
| TimeBodyGyroMean-Z                    | are neat      |    g as a 128 element vector |
| TimeBodyGyroSTD-X                     | are neat      |    g as a 128 element vector |
| TimeBodyGyroSTD-Y                     | are neat      |    g as a 128 element vector |
| TimeBodyGyroSTD-Z                     | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkMean-X                | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkMean-Y                | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkMean-Z                | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-X                 | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-Y                 | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkSTD-Z                 | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationMagnitudeMean     | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationMagnitudeSTD      | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationMagnitudeMean  | are neat      |    g as a 128 element vector |
| TimeGravityAccelerationMagnitureSTD   | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMagnitureMean | are neat      |    g as a 128 element vector |
| TimeBodyAccelerationJerkMagnitureSTD  | are neat      |    g as a 128 element vector |
| TimeBodyGyroMagnitureMean             | are neat      |    g as a 128 element vector |
| TimeBodyGyroMagnitureSTD              | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkMagnitudeMean         | are neat      |    g as a 128 element vector |
| TimeBodyGyroJerkMagnitudeSTD          | are neat      |    g as a 128 element vector |
| FreqBodyAcceleration-Mean-X           | are neat      |    g as a 128 element vector |
| FreqBodyAcceleration-Mean-Y           | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationMean-Z            | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationSTD-X             | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationSTD-Y             | are neat      |    g as a 128 element vector |
| FreqBodyAccerlationSTD-Z              | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-X        | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-Y        | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMean-Z        | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-X         | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-Y         | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkSTD-Z         | are neat      |    g as a 128 element vector |
| FreqBodyGyroMean-X                    | are neat      |    g as a 128 element vector |
| FreqBodyGyroMean-Y                    | are neat      |    g as a 128 element vector |
| FreqBodyGyroMean-Z                    | are neat      |    g as a 128 element vector |
| FreqBodyGyroSTD-X                     | are neat      |    g as a 128 element vector |
| FreqBodyGyroSTD-Y                     | are neat      |    g as a 128 element vector |
| FreqBodyGyroSTD-Z                     | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationMagnitudeMean     | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationMagnitudeSTD      | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMagnitureMean | are neat      |    g as a 128 element vector |
| FreqBodyAccelerationJerkMagnitureSTD  | are neat      |    g as a 128 element vector |
| FreqBodyGyroMagnitureMean             | are neat      |    g as a 128 element vector |
| FreqBodyGyroMagnitureSTD              | are neat      |    g as a 128 element vector |
| FreqBodyGyroJerkMagnitudeMean         | are neat      |    g as a 128 element vector |
| FreqBodyGyroJerkMagnitudeSTD          | are neat      |    g as a 128 element vector |

