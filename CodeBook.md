# Introduction

# Overview

The script `run_analysis.R`performs the 5 steps described in the course project's definition.

* Merges the training and the test sets to create one data set using the `rbind()` function.
* Name the measurement columns after the feature names, and give names to the id columns.
* Create a new data frame whose measurement columns contain only mean and st. dev features.
* Trim the rows to the 180 needed to show mean values for each subject-activity pair.
* From the data set in previous step, creates a new tidy data set with the average of each variable for each activity and each subject.

# Variables

* `x_train`, `y_train`, `x_test`, `y_test`, `subtrain` and `subtest` store the data from the downloaded files as we read the data files into R:
* `xall`, `yall` and `suball`  merge all downloaded data into one database `allofit`.
* Name the measurement columns after the feature names, and give names to the id columns resulting in `allofit` with correct names for the dataset.
* Create a new data frame whose measurement columns contain only mean and st. dev features
* Trim the rows to the 180 needed to show mean values for each subject-activity pair
* Rename and output the data to "Tidy_Data.txt"

