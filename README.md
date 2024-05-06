# DataProcessing

This python file uses Pandas-Data Manipulation Library, Joblib-Parallel processing library to convert a large data file which contains lexical information about users and their lexical knowledge in English while their native speaking language is Arabic into a desired shape. In the final file the columns represent the words, and rows indicate the number of users who has accuratley answered the words presented to them with no less than three errors.

The required information of the users is distributed in three files namely profiles.csv,sessions.csv, lexical-decision.csv.
The column common to any two files is used to combine the user information to create a final entry in the output file.
