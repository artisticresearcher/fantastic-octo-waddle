As per the script run_analysis.R 
1. features - features from the features.txt database come from the accelerometer and gyroscope
2. activities - list of activities performed when measurements were taken
3. subject_test - contains test data from subjects owning the Samsung Galaxys
4. x_test - contains recorded features test data
5. y_test - contains test data of activities' code labels
6. subject_train - contains train data of volunteer subjects
7. x_train - contains recorded features train data
8. y_train - contains train data of activities' code labels

1. X - merged x_train and x_test
2. Y - merged y_train and y_test
3. Subject - merged subject_train and subject_test
4. Merged_Data - merged X, Y and Subject

TidyData - subsetting Merged_Data selecting only columns: subject, code and mean and standard deviation.

1. code column is renamed into activities
2. Acc - accelerometer 
3. Gyro - Gyroscope
4. BodyBody - Body
5. Mag - Magnitude
6. f - Frequency
7. t - Time

