# Getting and Cleaning Data - Course Project
This is the final project for Getting and Clearning Data. The script created in this project, run_analysis.R, is capable of the following:

1. If the dataset does not already exist in the working directory, downloads the dataset
2. Loads the activity and feature info
3. Loads the columns for the training and test datasets that show a mean or SD
4. Merges the columns from each activity and subject data for each dataset
5. Merges both datasets
6. Converts the activity and subject columns into factors
7. Creates dataset showing the mean of each variable for subject and activity combination

Final results can be seen in tidy.txt.
