# XML-2-PDO_MYSQL
Automatically insert any XML fields into MYSQL using PDO/Prepared Statements 


Description:

This small snippet of code allows easily inserting XML fields into MYSQL without needing to use the mysqli_real_escape_string command for every variable. It can handle nested arrays of varying lengths, and doesn't break the insert command if there is an apostrophe or other special character in the data.


