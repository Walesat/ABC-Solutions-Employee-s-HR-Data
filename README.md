# Data Analysis - Training Tasks

EXCEL TASK 1

**For this task, we were required to create a table with 20 rows of information having the fields: Employee ID, Employee Full Name, Department, Salary and Job type**.

I designed a table and came up with random names. For the employee ID, I used a straightforward identification method. Then the remaining columns were also randomnly chosen.
To enhance the visibility, I applied borders to the datasets and added background color to the column headers. I named the worksheet as "Sheet0" then I duplicated the datasets onto Sheets 1,2, and 3, as i had additional tasks to carryout within the same worksheet.

![](Sheet0.png)

**For sheet 1, I was asked to show only employees who are 'Freelancers' and highlight the ones whose salaries are above $10,000**

I began by selecting the 'job type' column and applied a filter, narrowing down the results to display only the freelance employees. Following that, I employed conditional formatting in the 'salary' column to emphasise salaries exceeding $10,000.

![](Sheet1.png)

**For sheet 2, I was asked to split the employees full names into first name and last name, and check for duplicates and highlight if there are any.**

To achieve this, I utilized the 'Text to Columns' feature found on the 'Data' tab in Excel. Initially, I inserted an additional column following the 'Employee Name' column. Then, I selected the 'Employee Name' column and accessed the 'Text to Columns' option on the 'Data' tab.
The data type 'Delimited' was already chosen, so I proceeded to the next step. I selected 'Space' as the delimiter and continued to the subsequent step. The data type was already set to 'General,' and the destination column was automatically designated as the current column. 
Upon clicking 'Finish,' I was prompted if I wanted to replace the data in the column, to which I responded with yes. As a result, the first and last names were successfully separated into the selected column and the newly created one. Notably, there were no duplicates present.

![](Sheet2.png)

**For the last sheet, I had to highlight employees whose names begin with the letter E in yellow and format the salary column such that the highest salary has a green background, and the lowest salary has a red background**

Firstly, I choose the 'Employee Name' column. Afterward, I navigated to the 'Conditional Formatting' menu and clicked on 'Highlight Cell Rules.' From there, I selected 'More Rules.'
I proceeded to modify the rule description to specify that only cells containing text commencing with 'E' should be formatted, and I assigned the color yellow for this formatting.
Subsequently, I organized the 'Salary' column in descending order, arranging it from the largest to the smallest values. Lastly, I applied the 'Green-Yellow-Red' color scale in the 'Conditional Formatting' options to emphasize the salary range

![](Sheet3.png)

**EXCEL TASK 2**

**For this particular assignment, we received a financial dataset from a company. This dataset comprises 700 rows of data with 16 different columns**

The data was clean and requiring only a few adjustments. Initially, I resized the column widths to match their content. Subsequently, I applied color to the header columns and centered them for better visibility. Then, I proceeded to adjust the data types for each column: currency for monetary values, date for dates, text for text-based information, and general for the remaining data.

**The first task was to calculate the Total Revenue and Profit generated.**

To compute the Total Revenue, I utilized the SUM function on the entire sales column.

![](SC1.png)

The Total profit was gotten from summing up the profit column using the SUM function.

![](SC2.png)

  - The Total Revenue was determined to be £118,726,350.26, and the Total Profit amounted to £16,893,702.26.


**The second task was to find the Average Revenue and Units Sold for each order.**

To obtain the Average Revenue, I applied the **AVERAGE** function to the sales column.

![](SC3.png)

I also used the AEVRAGE function to get the **Average** units sold

![](SC4.png)

  - The Average Revenue equated to £169,609.07, and the Average Units Sold stood at 1608.29.

**The subsequent task was to ascertain the Total Discount given in £.**

In this instance, I used the SUM function on the discount column.

![](SC5.png)

  - The Total Discount given was calculated to be **£9,205,248.24**.

**The next task was to determine the Total number of sales recorded.**

The total number of sales recorded was determined by Summing the units sold and this was to the tune of **1,125,806**

![](SC6.png)

**The subsequent task was to identify the Highest Profit generated.**

I accomplished this by employing the **MAX** function on the profit column.

![](SC7.png)

   - The Highest Profit was found to be £262,200.00.

**The final task involved creating a column named 'Sales Range,' classifying it as 'High Sales' if the Sales value exceeded the average and 'Low Sales' if otherwise.**

To achieve this, I introduced a new column titled 'Sales Range' and used the IF function. By referencing the sales column with absolute references to the cell containing the average sale value, I categorized the data.

![](SC8.png)

   - The results showed 472 records classified as Low Sales, while the remaining entries fell under the category of High Sales.
