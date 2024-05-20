The Data Analysis of Sales of Value Inc by utilizing the Library of Python named pandas.

The steps are as followed:

1- I read the csv file using the Pandas read_csv function.
2- After that I performed various calculation on columns to create new columns which are:Cost Per Transaction,Selling Price Per Tansaction, Profit per Transaction & Mark up per Transaction.
3- The columns markuptransaction was rounded to two decimal places.
4- The Day and Year column was converted to datatype as String in order to create a new column named Date column.
5- I use the iloc function to view the rows and columns of the dataset.
6- Split and replace function is used to split the columns into various columns such as ClientAge,ClientType & Length of Contract and replace is used to change the brackets[].
7- One of the columns Item Description was changed to Lower Case.
8- A merge function was used to add two files together with the merging column is Month.
9- Column which are of no use are removed such as ClientKeywords,Day,Year & Month using Axis.
10- In the end the new cleaned data was used to create a new file ValueInc_Cleaned.csv using the function data.to_csv.

Dashbard building using Tableau:

The dashboard is built using Tableau and is comprises of various charts such as:
Sales per Month:it is a Line Chart which takes two variables into account Month vs Sales per transaction.
Cost per Month:it is also Line Chart which takes two variables into account Month vs Cost per transaction.
Profit by Client Age:it is a Bar Chart which takes two variables into account Categories of Age vs Profit per transaction.
Profit by Client Type:it is also a Bar Chart which takes two variables into account Categories of Client Type vs Profit per transaction.
Profit per Month:it is a Line Chart which takes two variables into account Month vs Profit per transaction.
Profit by Item Code:it is a Horizontal Bar Chart which takes two variables into account Profit per transaction vs Item Code.
Profit by Country:it demostrate the various Profit based on the countries of the world.
