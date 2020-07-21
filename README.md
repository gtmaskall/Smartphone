# Smartphones and Motion

### Background

This project will classify human movement using data obtained from smartphones.

The data comes from University California Irving's Machine Learning Repository and has been analyzed in [Kaggle](https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones).  In a nutshell, accelerometer and gyroscope sensors were embedded in smartphones to capture signals from people performing different kinds of activity.  

Each row (observation) in the summary files is a "window".  A window is characterized by 516 features.  These features were calculated from time and frequency raw data.  128 raw data readings were collected per window. 

Each window is associated with a particular subject performing one of the following six activities:

* 1 WALKING
* 2 WALKING_UPSTAIRS
* 3 WALKING_DOWNSTAIRS
* 4 SITTING
* 5 STANDING
* 6 LAYING

There are a total of 30 subjects.  70% of the subjects were partitioned into the training data set.  The remaining 30% were designated as test subjects to assess models.

This project will span multiple Phases:

* Phase 1
    * Wrangle the data into a format conducive for analysis
* Phase 2
    * Explore and summarize data
* Phase 3
    * Develop classification models
* Phase 4
    * Assess models
    
### Data

The original data, dated 2012-12-10, can be downloaded [here](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) after clicking on the "Data Folder" link.  Data processing will be conducted in RStudio.

### License

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. 
