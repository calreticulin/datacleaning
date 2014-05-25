============================
Code Book for run_analysis.R
============================

Data Cleaning Process
============================
- read trainset, trainlabels and combine them
- properly label variables with the names given in features.txt
- properly label activities with names given in activity_labels.txt
- extract mean and std by feature names
- using ddply to construct new table where average is applied on (subjects, activitis) 
- output table to output.csv  

============================

Variables
============================
- subjects: id of the experiment subjects, range from 1:30
- activities: activities, including: "WALKING", "WALKING_UPSTAIRS", "WALKING_DOWNSTAIRS", "SITTING", "STANDING", "LAYING"
- measures: see feature_infos.txt  

============================
