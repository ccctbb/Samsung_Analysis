<h3>Variables used in processing (and provided in initial data set see features.txt and features_info.txt):</h3>
<h4>activityLabels <br /></h4>
  1 WALKING <br />
  2 WALKING_UPSTAIRS<br />
  3 WALKING_DOWNSTAIRS<br />
  4 SITTING<br />
  5 STANDING<br />
  6 LAYING <br />


<h4>labels</h4>
  measurements of various telemetric data from the smart phone, in 3-dimensions. (see features.txt)
  
<h8>variable labeled test are from a subset of volunteers as a control group. 
variable labeled with train are volunteers participating in the training study.</h8>
<br />  <h4>subject_test, y_train </h4>= volunteers numbered 1 thru 30
<br />  <h4>y_test, y_train </h4>= activity 1 thru 6
<br />  <h4>x_test, x_train </h4>= telemetric measurements over complete set of variables
  
<h3><h4>all_data</h4> is the complete data set 

<H8> processing notes included in variable descriptions</h8>

<h4>selectData</H4> is the subset of all_data filtered for only mean and standard deviation measurements

<H4>subjectData</H4> is a split over selectData by subject (volunteer)

<H4>finalData</H4> is the stratified data frame, each row is the mean of the sets of measurements for a 
particular subject engaged in a particular activity.</h3>


