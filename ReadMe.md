This is the Read Me for the tidydata.txt file.

The file was created from the Samsung S3 Data Set which can be seen [here](https://github.com/kythryn/dsmonth3/tree/master/UCI%20HAR%20Dataset%202). The steps to create the data set are as follows.
The step numbers are also included as comments in the code.

#Step 1: reading in the data
Pulls in all of the data to construct the table

#Step 2: Constructing the data table
Combining training and test data. Adding features as column names, and subjects and activities as row names

#Step 3: Extracting only mean and standard deviation columns
I did this by hand, examing the full table and selecting those which were either means or SDs. Converted Activites to Factors and all other columns as integers

#Step 4: Adding sensible column names
Rewrote all the column names to be human readable. The conversions can be seen in the code book

#Step 5: Subsetting by combinations of subject and activity
Takes all 180 combinations of Subject(1-30) and Activity(1-6) and subsets for each, calcuating the mean across the selected row as we go. There is probably a way of scripting this but I couldn't work it out, hence the 180 lines of code.

#Step 6: Creating a new table from the subsets.
Recombines all of my subsetted data into a new table.
Re-attaches sequences of subject number and activity name to the new table

#Step 7: Outputting table file
Creates tidydata.txt as shown in this repository.

