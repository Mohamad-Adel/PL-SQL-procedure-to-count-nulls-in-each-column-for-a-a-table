# PL-SQL-procedure-to-count-nulls-in-each-column-for-a-a-table
A simple procedure to take a table name as an input from the user and print out the name of each column, count of null values in that column, and to print "not nullable" in case of zero nulls in that column

Execution(With Out Errors):
exec table_null_columns('Departments');



Execution(In Case of an Error):
exec table_null_columns('Departts');
