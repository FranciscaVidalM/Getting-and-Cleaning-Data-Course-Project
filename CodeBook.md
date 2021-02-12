# Getting and Cleaning Data Project

## Review criteria: 
1. The submitted data set is tidy
2. The Github repo contains the required scripts
3. GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information
4. The README that explains the analysis files is clear and understandable
5. The work submitted for this project is the work of the student who submitted it

## Modifications to the original data set:
1. Merged the training and the test sets to create one data set
2. Extracted only the measurements on the mean and standard deviation for each measurement
3. Used descriptive activity names to name the activities in the data set
4. Appropriately labeled the data set with descriptive variable names
5. From the data set in step 4, created a second, independent tidy data set with the average of each variable for each activity and each subject

## Data description
1. SubjetcNum: the id of the subject
2. Activity: Name of the activity performed by the subjetctNum when the mesurements where done
3. Measurements: mean and standard deviation calculated from the sets of data 
Eg. 
tBodyAcc-mean-X
tBodyAcc-mean-Y
tBodyAcc-mean-Z
tBodyAcc-std-X
tBodyAcc-std-Y
tBodyAcc-std-Z
tGravityAcc-mean-X
tGravityAcc-mean-Y
tGravityAcc-mean-Z


