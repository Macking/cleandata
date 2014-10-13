cleandata
=========

This file explains how the scripts of this repo work.

The R script run_analysis.R can download and process the required data. Then, it creates two new tidy data sets:

data_set.txt : combines training and test data sets (together with subject and activity data).

average_vbles.txt : aggregates the aforementioned data by subject and activity (the mean of multiple trials for each feature is taken).

Source

Information about used data in: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Used data set: zip file (NOTE: the R script created will download it from the source if necessary).

Dependencies

run_analysis.R depends on reshape2 and plyr libraries (NOTE: The R script created will install and load them if necessary).