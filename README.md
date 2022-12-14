# HHA-Data-Cleaning

Download the recently published dataset from healthdata.gov called “School Learning Modalities” - https://healthdata.gov/National/School-Learning-Modalities/aitj-yx37 - and place it into your new repo, and inside a new sub-folder inside of the repo
called ‘data’.

Please write either a .py script
or a Jupyter notebook (.ipynb) file that performs the following on the dataset:


1.     Loads the data into python


2.     Prints the count of columns and rows


3.     Provides a print out of the column names


4.     Cleans the column names


5.     Cleans the strings that might exist within each column


6.     Assesses white space or special characters


7.     Converts the column types to the correct types (e.g., DOB field is datetime and not object


8.     Look for duplicate rows and remove duplicate rows


9.     Assess missingness (count of missing values per column)


10.  New data field: attempt to create a new column called modality_inperson.  This
column should contain a binary value of true or false. Try to write a function that takes in the old column
name (learning modality), and recodes the value for a specific row to true, if
the learning modality value is ‘in-person’, and recodes it to false if the value
is either ‘remote’ or ‘hybrid’
