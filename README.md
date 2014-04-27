GettingAndCleaningDataPeerAssignment
====================================

The run\_analysis() script transforms the Samsung data into a tidy format. The data should be located in the UCI HAR Dataset-folder in the working directory. The script produces two text files, "data.txt" and "averages.txt.". The "data.txt" file contains the whole data set (with columns containing "mean()" or "std()"  in their name only. 

The script first loads the data in the load\_data() function. This function loads the data, filters the columns, and combines the test and train sets into one data frame. It utilizes the load\_type_data() function, which reads the subjects\_xxx.txt file, the activity data in the y\_xxx.txt file, and the recorded data in the X\_xxx. file. 

Next the script labels the activities with descriptive names in the name\_activities() function. The activities are read from the activity\_labels.txt file. 

Then the script creates a summary of the data by calculating the averages of the recorded data for each features by avtivity and subject. This is done in the create\_summary() function. This function uses the simplify\_summary() and the simplify\_subject\_list\_element() functions to tidy up the transformed data. The function also sort the average data by activity and subject

Lastly the run\_analysis() script write the two data frames to their respective files. 

