Samsung_Analysis
================

analysis of smart phone data- provides analysis measurements of 30 subjects performing 6 activities
 ----------------
 
 run_analysis.r 
 
 Uses library(reshape2) and library(foreach)  -- packages should be installed before sourcing.
 
 Further assumption that DATA is structured thus:
 
   {working directory}
   activity_labels.txt
   features.txt
   train/
       x_train.txt
       y_train.txt
       subject_train.txt
   test/
       x_test.txt
       y_test.txt
       subject_test.txt
       
further introductory and descriptive information for the basis of the project may be found here:
    http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
    
initial datasets and details are here:
    https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
