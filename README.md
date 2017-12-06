# CONTENTs of THIS REPO: Getting_and_Cleaning_Data_Course_Assignment
Coursera final peer reviewed assignment for course 3 of Learning R

# Run_analysis.R:

This is the script that will get you a tidy dataset for this assignment. It will download the zip file from the URL and unzip it for you.
IMPORTANT! Set your working directory first before running this script. 
This script has ## symbols defining the steps and briefly describes what it does.

Follow ## in script to define the following steps:

Goal: Create a data set with the average of each variable for each activity and each subject.

Step 1:
Load packages.

Step2:
Download the file. Put it in the 'Data' folder (this is the working directory in my case).

Step3:
Unzip the file in the working directory.

Step4:
The archive put the files in a folder named 'UCI HAR Dataset'. Set this folder as the input path. List the files here.

Step5:
Read the subject files, then read the the activity files, and finally read the data files.

Step6:
Merge the training and test sets by concatenating the tables.

Step7:
Extract the means and SDs.

Step8:
Label the columns with 'descriptive variable names'.

FINAL:
Create a tidy data set! Print key and summary !!accomplishing the goal!! --



# tidy_data.txt:

the output from the script run.analysis.r, a tidy dataset. --

# key_description_for_tidy_data:

Lists all variable names and a brief description what this variable is.
