Project Title:
Event Details - Data Cleaning Project in Excel.
Source File : Eventdetailsdatacleaningexcel.xlsx
Output File : dataclean.xlsx

This Project helped me to apply my Excel skills and techniques typically used by data analysts to explore,clean, and analyze eventdetails data. 

This project involves Concepts of:

•	Combining Two Datasets
•	Extracting Data from a Column
•	Removing Duplicate Values
•	Handling Missing Values
•	Spelling Mistakes
•	Date Format Issues
•	Number (currency) Issues

Objectivies:
Set up a Event Details data: Create and populate a Event Details data with the provided data.
Data Cleaning: Identify and remove any records with missing or null values.
Exploratory Data Analysis (EDA): Perform basic exploratory data analysis to understand the dataset.
Data Analysis: Use Excel techniques to answer specific business questions and derive insights from the events data.

Expected Output:
A neat 6 column table with Person, City, Ticket Price, Date, Time, Event Detail columns.
The data should not contain any duplicate rows, typos, spelling mistakes and format issues
Any missing values are identified with yellow color shading

Project Structure:
1. Copy the two tables to a new excel worksheet and name the tables - dataset 1,2
2. Create a new column Person clean with the help of trim function to remove space
3. Find the blank cells in columns city and ticket price and fill it with a color to identify easily.
4. Open a new workbook for clean data and use the get data option to get the datasets from the source file
5. Use the dataset 2 and make new table with 4 columns
6. Check the column headings are same in both the tables if not change the headings before appending
7. Append 2 tables to get  a new table
8. Check for null values in ticket price and assign TBA for those values
9. Filter all the bullet values in the event detail column 
10. Make a new query for the city column and remove duplicates and see the values
11. Create a notepad file of these values and put the new values next to it.
12. Now delete query and create new query from file- which has city names
13. Map the city and the city names (check if it is correct and null values)
14. Replace the null values with TBA in city.
15. Now split the event detail column to get the date and time.
16. Convert the data type of Event Date to date type
17. Ticket price null values to TBA
18. Load only the final data to new excel file
19. Update the source file and see the power query is refreshing

Data Analysis:
1. I want to see event details that is happening in New York.
   ![image alt](https://github.com/nsankareswari-70/ExcelDatacleaning1/blob/9c9057cbe45656978dbc6a09b93e36928d9d3a44/P1.png)


2  Get the event details for a particular date?
![image alt](https://github.com/nsankareswari-70/ExcelDatacleaning1/blob/1d1b1483f3ab70bd7ecaef97bae5210cb9e465cd/P2.png)

3. Find all the events Katy Ferry is attending?
![image alt](https://github.com/nsankareswari-70/ExcelDatacleaning1/blob/1d1b1483f3ab70bd7ecaef97bae5210cb9e465cd/P3.png)

Conclusion:
This project serves as a comprehensive introduction to Excel for data analysts, covering data setup, data cleaning, exploratory data analysis, and business-driven Excel questions. The findings from this project can help drive business decisions by understanding Citywise Events, Events happening on a particular date, or to find out the events a particular person is attending. (Here i pulled the records for Katy Ferry).

End of Project.
Thank You


