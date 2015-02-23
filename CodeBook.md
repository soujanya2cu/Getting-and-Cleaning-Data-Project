1. Merge the training and the test sets to create one data set.

read the txt files using read.table command and saved.

features.txt
activity_labels.txt
subject_train.txt
x_train.txt
y_train.txt
subject_test.txt
x_test.txt
y_test.txt

Assign column names and merge the datasets using rbind function.

2. Extract only the measurements on the mean and standard deviation for each measurement.

grep the values for mean and stdev columns and Subset this data to keep only the necessary columns.

3. Use descriptive activity names to name the activities in the data set

used names argument to name the activities in the dataset.

4. Appropriately label the data set with descriptive activity names.

5. Create a second, independent tidy data set with the average of each variable for each activity and each subject.

used the ddply function to create the average dataset.

Loaded the Plyr library to use the required function ddply