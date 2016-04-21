# GettingAndCleaningData Project

This repository holds the R source code, run_analysis.R, and documentations.

The dataset for this project  is:  [Human Activity Recognition Using Smartphones](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

# Files

The code downloads the dataset file (if the zip file does not exists) from the source and un-compressed to the working directory, getwd().  If "UCI HAR Dataset" directory exists, the code assumes that the file has been unzipped.  Remove this directory, if you want the code to unzip again.

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

run_analysis.R contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output of the 5th step is called averages_data.txt, and uploaded in the course project's form.
