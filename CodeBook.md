Variables used in processing (and provided in initial data set see features.txt and features_info.txt):

activityLabels 
```sh
  1 WALKING
  2 WALKING_UPSTAIRS
  3 WALKING_DOWNSTAIRS
  4 SITTING
  5 STANDING
  6 LAYING 
```  

labels
  measurements of various telemetric data from the smart phone, in 3-dimensions. (see features.txt)
  
variable labeled test are from a subset of volunteers as a control group. variable labeled with train are
volunteers participating in the training study.
```sh
subject = volunteers numbered 1 thru 30
  y = activity 1 thru 6
  x = telemetric measurements over complete set of variables
```  
all_data is the complete data set 

selectData is the subset of all_data filtered for only mean and standard deviation measurements

subjectData is a split over selectData by subject (volunteer)

finalData is the stratified data frame, each row is the mean of the sets of measurements for a 
particular subject engaged in a particular activity.


