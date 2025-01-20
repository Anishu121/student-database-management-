# student-database-management-
A simple project that will contain the basic information about the students

This Python application is a Student Information System built with the Tkinter library for the GUI and pymysql for database connectivity. It allows users to manage student data, including adding, updating, deleting, searching, and displaying student records.

# Features
Add Student Records: Save student details, including enrollment number, name, class, section, course, contact, father's name, address, gender, and date of birth.
Update Records: Modify existing student information.
Delete Records: Remove student records using the enrollment number.
Search Records: Find a student using their enrollment number.
View All Records: Display all student records in a table format.
Clear Fields: Reset all input fields for a fresh entry.

# GUI Layout
Input Fields: Located on the left panel, allowing users to enter and modify student details.
Action Buttons: Add, Update, Delete, Clear, Search, and Show All are located in the respective sections.
Data Table: Located on the right panel, displaying all student records.
Code Overview
GUI: Built using Tkinter, with various widgets like Label, Entry, Button, Treeview, and Scrollbar.
Database Operations: Uses pymysql to interact with the MySQL database.
Core Functions:
add_func: Inserts a new record.
fetch_data: Displays all records in the table.
get_cursor: Populates fields based on the selected row.
update_func: Updates an existing record.
delete_func: Deletes a record.
search_func: Searches for a record by enrollment number.
clear: Resets all input fields.
