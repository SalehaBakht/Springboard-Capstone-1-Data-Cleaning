# Section 5 Submission - Data Cleaning of Chocolate Rating Dataset from Kaggle

The purpose of the section 5 submission is to practice data wrangling and cleaning. I did this on the Chocolate Bar Rating dataset gotten from one of the Kaggle competitions.

First I replaced all the column names so that there were no line breaks in the names.

Then, I checked to see where the null values were in all of the columns. 

For the columns that had no null values, I checked their content for spelling and datatype. Spelling was corrected if found. Only the Cocoa Percent columns had to change datatypes as it came in datatype Object written with percentages. It was converted to a float type to allow for easier manipulation in future explorations. 

After searching for null values, the two columns found remaining with null values were the ‘Bean Type’ and ‘Broad Bean Type’ columns.

For ‘Broad Bean Origin’, the null values were replaced with the corresponding value from the ‘Specific Bean Origin or Bar Name’ column. That only provided a value for one row and still left a host of other empty cells in the ‘Broad Bean Origin’ column.
