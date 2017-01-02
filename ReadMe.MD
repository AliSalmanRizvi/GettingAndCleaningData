This is with regards to the project assignment for the Getting and Cleaning Data course at Coursera. 

As part of the same, the script run_analysis.R has been created with following steps:

1. Download the dataset if it does not already exist
2. Load the activity and feature info
3. Load both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Load the activity and subject data for each dataset, and merges those columns with the dataset
5. Merge the two datasets
6. Convert the activity and subject columns into factors
7. Create a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The end result is shown in the file tidy_dataset.txt.