Rcleaning
=========

Functions for cleaning data in R.

combineRows function: takes a dataframe that has multiple records for a primary key and combines the contents in each column
so there's exactly one record per primary key. 

breakfile function: This function takes a path and file for a csv file (entered in quotes, with / to divide the path beginning at one's default R path) and an integer and breaks that file into smaller files of that number of records. If there are records remaining, then the final file will contain the remaining records.
