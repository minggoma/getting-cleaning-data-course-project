# getting-cleaning-data-course-project


The run_analysis.rmd file contains code to run the desired analysis on the Samsung data set.

The analysis performs the following:

- Reads in data from the features.txt file
- Reads in data from the activity_labels.txt file
- Reads in the testing data and merges the files
- Reads in the training data and merges the files
- Data cleans both the testing and training data and merges both together
- Renames the variable names per the names in the features.txt file
- Renames the activity labels using the names in the activity_labels.txt file
- Selects only the variable names that have an associated mean and std and does not select for and columns that have mean frequency
- Calculates the mean of each variable for a given subjectid and a given activity
- Renames all variables to be all lowercase with letters only add added "mean" to the end to identify that all values in the table are means

The variable names are as follows:
"subjectid"
"activitylabel"
"tbodyaccmeanxmean"
"tbodyaccmeanymean"
"tbodyaccmeanzmean"
"tbodyaccstdxmean"
"tbodyaccstdymean"
"tbodyaccstdzmean"
"tgravityaccmeanxmean"
"tgravityaccmeanymean"
"tgravityaccmeanzmean"
"tgravityaccstdxmean"
"tgravityaccstdymean"
"tgravityaccstdzmean"
"tbodyaccjerkmeanxmean"
"tbodyaccjerkmeanymean"
"tbodyaccjerkmeanzmean"
"tbodyaccjerkstdxmean"
"tbodyaccjerkstdymean"
"tbodyaccjerkstdzmean"
"tbodygyromeanxmean"
"tbodygyromeanymean"
"tbodygyromeanzmean"
"tbodygyrostdxmean"
"tbodygyrostdymean"
"tbodygyrostdzmean"
"tbodygyrojerkmeanxmean"
"tbodygyrojerkmeanymean"
"tbodygyrojerkmeanzmean"
"tbodygyrojerkstdxmean"
"tbodygyrojerkstdymean"
"tbodygyrojerkstdzmean"
"tbodyaccmagmeanmean"
"tbodyaccmagstdmean"
"tgravityaccmagmeanmean"
"tgravityaccmagstdmean"
"tbodyaccjerkmagmeanmean"
"tbodyaccjerkmagstdmean"
"tbodygyromagmeanmean"
"tbodygyromagstdmean"
"tbodygyrojerkmagmeanmean"
"tbodygyrojerkmagstdmean"
"fbodyaccmeanxmean"
"fbodyaccmeanymean"
"fbodyaccmeanzmean"
"fbodyaccstdxmean"
"fbodyaccstdymean"
"fbodyaccstdzmean"
"fbodyaccjerkmeanxmean"
"fbodyaccjerkmeanymean"
"fbodyaccjerkmeanzmean"
"fbodyaccjerkstdxmean"
"fbodyaccjerkstdymean"
"fbodyaccjerkstdzmean"
"fbodygyromeanxmean"
"fbodygyromeanymean"
"fbodygyromeanzmean"
"fbodygyrostdxmean"
"fbodygyrostdymean"
"fbodygyrostdzmean"
"fbodyaccmagmeanmean"
"fbodyaccmagstdmean"
"fbodybodyaccjerkmagmeanmean"
"fbodybodyaccjerkmagstdmean"
"fbodybodygyromagmeanmean"
"fbodybodygyromagstdmean"
"fbodybodygyrojerkmagmeanmean"
"fbodybodygyrojerkmagstdmean"
