Getting-and-Cleaning-Data-Project
=================================

## Description

According the Course Project's Framework, this repo contains the necessary files for the assignement in the Data Science specialization course *Getting and Cleaning Data*.

## Repo's Contents

This repo contains the following files:

* the current `README.md` file which describes HOW TO USE the files of this repo and FILES' CONNECTIONS (how they are connected).
* the `codebook.md` which describes each variable in the output .txt file, the data and the steps in data cleaning process by providing a description of any transformations and/or work to clean up the data .  
* the `run_analysis.R` file which is a script written in R to perform our data cleaning.
* the `tidy_data.txt` file which is the output of our data cleaning process.

## HOW TO USE repo's contents

* First Assumption: the `run_analysis.R` file exists in the current working directory.
* Second Assumption: the contents of the `getdata_projectfiles_UCI HAR Dataset.zip` file is unzipped in the current working directory. (for downloading [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip ))

In order to get the output file, type `source("run_analysis.R")` in Rstudio. The output file "tidy_data.txt" will then be created in your working directory. If you wish to read the "tidy_data" in a table format then type `temp<-read.table("tidy_data.txt", header=TRUE)`, where the "temp" is a temporary variable (data.frame).
