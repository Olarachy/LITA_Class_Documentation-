# LITA Class Documentation-
## LADIES IN TECH ACADEMY 2024

LITA is a leading initiative committed to empowering women by providing technical training in the technology industry. Hosted by Incubator Hub and dedicated to Mummy G.O Folu Adeboye, LITA is designed to promote technological literacy among women and help them acquire critical skills for success in today’s digital world. The recently ongoing LITA training program featured various sessions on trending technologies, including data analysis, cloud computing, software development,digital marketing, content writting and others. The initiative serves as a platform for women to gain hands-on experience and mentorship from seasoned professionals who offered in-depth guidance throughout the training. LITA continues to play a pivotal role in uplifting women in tech, providing them with opportunities to learn, grow, and make an impact in the industry.
As one of the participant in Data Analysis class, i will highlight some of my take home.

## DATA ANALYSIS

### Microsoft Excel 

Excel: Data Entry, Data Validation, and Named Ranges

Excel is a powerful tool for data entry, and while inputting data into spreadsheets may seem straightforward, understanding the fundamentals of data entry, data formatting, and data validation is crucial. These skills not only make the process smoother but also help avoid common errors.

### **Data Entry Fundamentals**
1. **Understanding Data Types:** Excel recognizes two primary types of data: text and numbers. Ensuring your data is correctly categorized will help Excel function properly, especially when using formulas or data analysis tools.
2. **AutoFit for Cell Sizing:** To make sure all your data is visible, use the AutoFit feature to size the cells based on the content length. Simply double-click the boundary line between columns or rows when your cursor turns into a "+" sign.
3. **Navigation Shortcuts:**
   - **Tab Key:** Moves to the next cell in the same row.
   - **Enter Key:** Moves to the next cell in the same column.
   - **Shift + Tab:** Moves to the previous cell in the row.
   - **Shift + Enter:** Moves to the previous cell in the column.
4. **Using the Form Tool for Efficient Data Entry:** To make filling in data easier, you can use the Form tool. This tool is not always visible by default but can be added to the Quick Access Toolbar through customization.
   
### **Data Validation**
Data validation is essential for maintaining the integrity of your data by controlling the type of values that can be entered into a cell.
1. **Accessing Data Validation:** Click on the "Data" tab, then open "Data Validation" in the Data Tools group. 
2. **Setting Validation Rules:** You can define rules based on number format, lists, dates, or text length. These rules can be customized according to your specific needs.
3. **Error Alerts:** You can also set up custom error messages and alerts to guide users when incorrect data is entered, ensuring that the data remains consistent and accurate.
   
### **Named Ranges**
Named ranges allow you to assign a name to a group of cells, making it easier to reference them in formulas or when analyzing data.
1. **Creating a Named Range:** Go to the "Formulas" tab and select "Define Name." You can then assign a meaningful name to your selected range of cells.
2. **Using Named Ranges:** Once created, you can use these named ranges in formulas instead of cell references, making your spreadsheets easier to understand and maintain.

   ### Some Of Excel Shortcuts
   
- Ctrl + C / Ctrl + V:Copy and paste.
- Ctrl+ Shift+ Down Arrow: Select all below
- Ctrl+ Shift+ Up Arrow: Select all above
- Alt+A+V+V: Data Validation
- ctrl + A : Function arguement box
Ctrl + Arrow Keys: Quickly move to the edge of data regions
Ctrl + Z: Undo the last action.
Ctrl + A: Select all
Ctrl + ;(semi-colon) Enter the current date in a cell.
Ctrl + Shift + ;(semi-colon) Enter the current time in a cell.
Ctrl + Shift + "+" (Plus Sign) Insert a new cell, row, or column.
Ctrl + "-" (Minus Sign) Delete the selected cell, row, or column.
6. **Ctrl + D**  
   Copy the contents from the cell above into the current cell (fill down).
7. **Ctrl + R**  
   Copy the contents from the cell to the left into the current cell (fill right).
8. **Ctrl + ' (Apostrophe)**  
   Copy the formula from the cell above into the current cell.
10. **Ctrl + T**  
    Create a table from the selected range, which can make data entry more organized and easier to manage.
13. **Shift + F2**  
    Insert or edit a comment in the selected cell (useful for adding notes or instructions related to data entry).
15. **Ctrl + Shift + :**  
    Enter the current time in a cell
  
To access youtube video on Excel fundamental [click here](https://www.youtube.com/live/GbhNvK4uTtY?si=QtfjXVGOLmawPO8x])

### Excel Functions

1. SUM():

Adds a range of numbers.

Example: =SUM(D8:D27) adds values from cell D8 to D27.



2. AVERAGE():

Calculates the mean of a range of numbers.

Example: =AVERAGE(D8:D27) returns the average of values in D8 to D27.


MAX() and MIN():

Returns the largest (MAX) or smallest (MIN) value in a range.

Example: =MAX(D1:D10) or =MIN(D1:D10)





. AVERAGEIF():

Averages the values in a range that meet a specific condition.

Example:=AVERAGEIF(C8:C27,C20,D8:D27) averages the values in C8 to C27 rnage of cells, where C20 is the condition from values to look into D8:D27.



2. SUMIF():

Adds up the values in a range that meet a certain condition.

Example: =SUMIF(C8:C27,C9,D8:D27)



3. MAXIFS():

Returns the maximum value from a range that meets one or more criteria.

Example: =MAXIFS(D8:D27,C8:C27,C12)



4. COUNTIF():

Counts the number of cells in a range that meet a specific condition.

Example: = COUNTIF(C8:C27,C16)



4. IF():

Performs a logical test and returns one value if true and another if false.

Example: =IF(J2<=20,"low","Medium")
Nesting; Function in another Function
Example; =IF(J2<=20,"low",IF(J2<=50,"Medium","High"))


5. COUNT()/COUNTA :

Counts the number of cells that contain numbers while COUNTA count total number in text form.

Example: =COUNTA(B8:B27) counts the numeric cells in B8 to B27.


MID():

Extracts a specific number of characters from the middle of a text string.

Example: =MID(B123,3,6) returns 6 characters starting from the 3rd character in cell B123
.



2. LEFT():

Extracts a specified number of characters from the start (left side) of a text string.

Example: =LEFT(B123,2) returns the first 2 characters from the left of B123.

Use this when there space in text =LEFT(B6,FIND(" ",B6))



3. RIGHT():

Extracts a specified number of characters from the end (right side) of a text string.

Example: =RIGHT(B123,4) returns the last 4 characters from B123.

Use this when there is space in text =RIGHT(B6,FIND(" ",B6)-1)



4. PROPER():

Converts the first letter of each word in a text string to uppercase.

Example: =PROPER(G6) , =PROPER("G6 is jolly nyame") returns "Jolly Nyame."

PROPER AND TRIM

=PROPER(TRIM(B6))



5. & (Concatenation Operator):

Joins two or more text strings together. It’s similar to CONCATENATE().

Example:=B6&" "&C6 combines the values in B6 and C6 with a space in between.





6. CONCATENATE():

Joins two or more text strings into one.

Example: =CONCATENATE(A1, " ", B1) combines A1 and B1 with a space between.

3. VLOOKUP():

Searches for a value in the first column of a range and returns a value in the same row from another column.

Example: =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])
=VLOOKUP($E9,'Simple Salary Structure'!$B$8:O16,8,FALSE)

Excel Functions (https://www.youtube.com/live/Jb5ZHO8hIPY?si=AycIkU8Okdwh9smi)

PIVOT TABLE

A Pivot Table in Excel is a powerful tool used to summarize, analyze, explore, and present large amounts of data. It allows you to rearrange data dynamically to create different views and insights without changing the original data set.

Steps to Create a Pivot Table:

1. Select the Data on the table


2. Insert the Pivot Table:

Go to the Insert tab on the ribbon.

Click on PivotTable.

In the dialog box, confirm the data range and choose whether you want the pivot table in a new worksheet or in the existing one.



3. Build the Pivot Table: Once the PivotTable field pane opens:

Rows: Drag a field into the Rows area to categorize your data by that field (e.g., customer name, product, date).

Columns: Drag a field into the Columns area to break the data down further (e.g., month, region).

Values: Drag a field into the Values area to perform calculations, such as summing or counting data.

Filters: Drag a field into the Filters area to create filters to view a specific subset of data.

Example

Group data by month
click here for youtube video on pivot table https://www.youtube.com/live/Qufpy3ml6po?si=IS6kJT3HCtLH7Sda
also https://www.youtube.com/live/3vhDfmzCVxM?si=6PN6aWTvFy-JSFsK




Microsoft Excel is a powerful spreadsheet application widely used for data organization, calculation, and analysis. It enables users to store data in a structured format, perform complex calculations, and visualize data through charts and graphs. Excel’s versatility makes it a critical tool in various fields such as finance, project management, data analysis, and more. Its ability to handle large datasets, perform data cleaning, and automate repetitive tasks with macros increases efficiency and productivity. Excel is also equipped with features like PivotTables, which allow users to summarize and analyze data dynamically, and conditional formatting, which visually highlights critical insights. Understanding Excel is essential for anyone looking to work in data-centric roles, as it provides a solid foundation for further explorations in data analysis and business intelligence.

Excel Functions Excel functions are pre-built formulas that simplify complex calculations and automate data processing tasks. There are hundreds of functions in Excel, categorized under various domains such as mathematics, statistics, text manipulation, and logical operations. Some common Excel functions include SUM for adding values, VLOOKUP for searching data vertically in a table, IF for logical comparisons, and AVERAGE for calculating the mean of a dataset. These functions not only save time but also reduce the possibility of errors in manual calculations. Mastering these functions can transform Excel into a powerful tool for data manipulation and analysis, making it invaluable for professionals in data-driven environments.
Data Visualization


### SQL (Structured Query Language)<img width="609" alt="GRAPHICAL PRES" src="https://github.com/user-attachments/assets/ce81b504-d0de-43ff-b60c-b510f8194783">


SQL clauses https://www.youtube.com/live/n5SG2POhvrU?si=whq4C3q0ZJOib0qS

SQL, or Structured Query Language, is a standardized language used to interact with databases. It allows users to query, manipulate, and manage data stored in relational databases like MySQL, PostgreSQL, and SQL Server. SQL enables users to create tables, insert, update, and delete data, and retrieve information using SELECT queries. Complex data analysis can be performed using SQL commands like JOIN to combine data from multiple tables, GROUP BY for summarizing data, and ORDER BY for sorting results. SQL's ability to handle large volumes of data makes it indispensable in data analysis, business intelligence, and backend development. By understanding SQL, professionals can efficiently manage and interpret data, making it a crucial skill for anyone working in data-related fields.

```SQL
SELECT * FROM TABLE 1
WHERE CONDITION=TRUE
```




### GitHub

GitHub is a web-based platform that facilitates version control and collaborative software development. It leverages the Git version control system to track changes in code, manage project versions, and coordinate teamwork. Users can create repositories, which act as storage spaces for project files, and commit changes to keep track of every modification made to the project. Features like pull requests and branches allow developers to work on different aspects of a project simultaneously and review each other’s work before merging changes into the main project. GitHub is essential for software developers and teams working on collaborative projects, as it enhances code management, collaboration, and continuous integration.

Video on youtube [click here](https://www.youtube.com/live/p46Mkh0Lo68?si=alFTdIs0UcUjQOLY)
To get this, start with a colon and describe the emoji 😃
Creating a table
Heading
Referencing something already stated below
What you are referencing must have # and be in lower case. How important the trainig is [Conclusion](#conclusion)

To create table

| Heading 1 | Heading 2|
|-----------|----------|
| Content 1 | Content 2|


### Power BI

Power BI is a business analytics service provided by Microsoft that enables users to transform raw data into interactive dashboards and reports. It offers a user-friendly interface for data visualization, allowing users to connect to various data sources, perform data cleaning, and generate insights using drag-and-drop features. Power BI's visualizations include bar charts, line graphs, maps, and scatter plots, making it easier to identify trends and patterns in data. With its capability to handle large datasets, integrate with other Microsoft services, and provide real-time analytics, Power BI is widely used in business intelligence to drive data-informed decision-making. Mastering Power BI empowers users to create compelling data stories that facilitate better business strategies and performance tracking.

#### POWER BI FUNDAMENTALS
To see the youtube video on this [Click here](https://www.youtube.com/live/QFJ09s-NSR0?si=SAvPbrTdIRsmP5eu)

## CONCLUSION

The LITA training program has been a transformative experience for me, the dedication and efforts of our trainers—Mr. Idowu Muhsin, Mr. Femi Ayodele, Mr. Temitayo—and the supporting organizers have been commendable. Their commitment to providing in-depth knowledge and hands-on experience has had a tremendous impact on participants' professional growth. By empowering women with these skills, LITA has not only contributed to closing the gender gap in technology but has also fostered a culture of continuous learning and excellence. 

Thank you LITA Team!


