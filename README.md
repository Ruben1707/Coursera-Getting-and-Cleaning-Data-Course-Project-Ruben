# Coursera-Getting-and-Cleaning-Data-Course-Project-Ruben
Getting_and_Cleaning_Data_Course_Project_Ruben


    This is the course project for the Getting and Cleaning Data Coursera course.
    The included R script, run_analysis.R, conducts the following:

First, Download the dataset from web if it does not already exist in the working directory.
Second, Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
Third, Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to descriptive. (-mean to Mean, -std to Std, and remove symbols like -, (, ))
Also, Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, replace y(activity) column to it's name by refering activity label (loaded step 3).
By last, Generate 'Tidy Dataset' that consists of the average of each variable for each subject and each activity. The result is shown in the file tidy_dataset.txt.
