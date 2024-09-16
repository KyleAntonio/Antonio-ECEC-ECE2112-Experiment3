# Antonio-ECEC-ECE2112-Experiment3
##### General summaries of each problem. see main code for a more detailed breakdown
## Problem 1
##### Problem 1 involves displaying the first 5 and last 5 rows for a dataframe. The approach of this code is to filter the dataframe using the .index attribute for logical opration. By default, .index will produce the range or number of rows of the dataframe therefore it can be exploited such that one can set which rows to print using logical operators. In this case, setting the cars.index < 5 will produce the first 5 rows. We can then append this to a logical or operator so that it can also make an argument for the last 5 rows. In this case, instead of manually loading the dataframe to see which index the program is supposed to start from, we can use the .shape attribute then call index 0 to produce the scalar number of rows. From this, we subtract the desired number of rows starting from the last, which in this case was also 5, then it starts producing the indeces greater and equal to that number.

## Problem 2
##### Problem 2 involves extracting information from the dataframe using subsetting, slicing, and indexing operations (See main file for detailed breakdown as each problem is unique).
