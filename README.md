Download Link: https://assignmentchef.com/product/solved-itse-2309-database-programming-oracle-lab-5-data-manipulation-and-transaction-control
<br>
To perform the following assignments, refer to the tables created in the JLDB_Build_5.sql script.

<ol>

 <li>Add a new row in the ORDERS table with the following data: Order# = 1021, Customer# = 1009, and Order date = July 20, 2017.</li>

</ol>




<ol start="2">

 <li>Modify the zip code on order 1017 to 33222.</li>

</ol>




<ol start="3">

 <li>Save the changes permanently to the database.</li>

</ol>




<ol start="4">

 <li>Add a new row in the ORDERS table with the following data: Order# = 1022, Customer# = 2000, and Order date = August 6, 2009. Describe the error raised and what caused the error.</li>

</ol>




<ol start="5">

 <li>Add a new row in the ORDERS table with the following data: Order# = 1023 and Customer# = 1009. Describe the error raised and what caused the error.</li>

</ol>




<ol start="6">

 <li>Create a script using substitution variables that allows a user to set a new cost amount for a book based on the ISBN.</li>

</ol>




<ol start="7">

 <li>Execute the script and set the following values: isbn = 1059831198 and cost = $20.00.</li>

</ol>




<ol start="8">

 <li>Currently, the contents of the Category column in the BOOKS table are the actual name for each category. This structure presents a problem if one user enters COMPUTER for the Computer category and another user enters COMPUTERS. To avoid this and other problems that might occur, the database designers have decided to create a CATEGORY table containing a code and description for each category. The structure for the CATEGORY table should be as follows:</li>

</ol>
















<ul>

 <li>Create the CATEGORY table and populate it with the given data below. Save the changes permanently.</li>

 <li>Add a column to the BOOKS table called Catcode.</li>

 <li>Add a FOREIGN KEY constraint that requires all category codes entered in the BOOKS table to already exist in the CATEGORY table. Set the Catcode values for the existing rows in the BOOKS table, based on each book’s current Category value.</li>

 <li>Verify that the correct categories have been assigned in the BOOKS table, and save the changes permanently.</li>

 <li>Delete the Category column from the BOOKS table.</li>

</ul>




The data for the CATEGORY table is as follows:













Upload only the <strong>SQL Statements</strong> to Blackboard.


