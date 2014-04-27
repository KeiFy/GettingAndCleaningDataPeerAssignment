CodeBook
==========

See the link:
[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones ](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones )
for more info on the data. 

See the data:
[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip ](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )
and in particular the README.txt file and the features_info.txt file for more info on the data. 

The produced "data.txt" file contains both the test and train data in one data frame. Only columns including the strings "mean()" or "std()" are included. Activity and Activity\_code columns have been added, as according to the y_xxx.txt file. See activity\_labels.txt for more info. Also a Subject column has been added, as according to the subject\_xxx.txt file. 

The produced data "averages.txt" summaries the data by displaying the mean of each feature by activity and subject.