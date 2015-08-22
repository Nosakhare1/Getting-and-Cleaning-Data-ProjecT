# Getting-and-Cleaning-Data-ProjecT

My getting and cleaning data project. 
The R script, `run_analysis.R`, does the following:


i. It downloads the dataset if it does not already exist in the working directory                         
ii. Load the activity and feature info
iii. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
iv. Loads the activity and subject data for each dataset, and merges those columns with the dataset
v. Merges the two datasets
vi. Converts the 'activity' and 'subject' columns into factors
vii. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The final result exsist in the file tidy.txt. 
