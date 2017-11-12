The project has multiple classes and sub-classes with many features within them. Basic operations users can perform via this program project that are based on file handling are adding new employee record, modifying employee record and deleting record, displaying one or all employee’s record. Besides these, payroll management also allows users to print the salary slip for a particular employee. This project is large, complete and we tried our best to make it error-free. The source code is very long – over 1500 lines and developed in Code Blocks compiler.

# Project uses following c/c++ concept 
- Pointers
- Loops
- Functions
- If Else
- Switch
- Classes
- File handling
- C++ Graphics
- Function overriding and overloading
- Composition

# The Project classes
1. LINES
 * LINE_HOR
 * LINE_VER
 * BOX
 * CLEARUP
 * CLEARDOWN

1. MENUS
 * MAIN_MENU
 * EDIT_MENU
 * INTRODUCTION

1. EMPLOYEE
 * NEW_EMPLOYEE
 * MODIFICATION
 * DELETION
 * DISPLAY
 * LIST
 * SALARY_SLIP
 * ADD_RECORD   
 * MODIFY_RECORD
 * DELETE_RECORD
 * LASTCODE
 * CODEFOUND
 * RECORDNO
 * FOUND_CODE
 * DISPLAY_RECORD
 * VALID_DATE

# Project Operations
Addition of New Employee:  

This feature is under the public functions of class employee. The information handled in this feature are employee code number, name, address, phone number, joining date (day, month and year), designation, grade and loan.

Modify Employee Record: 

  This System in C++ asks for employee code from the user for this function to work. Modifications that can be made are the employee code number itself, joining date (day, month and year), name, address, phone number, designation, grade, house allowance and loan given to the employee. Employee’s grades are categorized as A, B, C, D and E.

Delete Employee Record: 

  Deletion is done of an employee record from Payroll management system project by entering the employee code. A confirmation message is asked stating whether the user really wants to delete the record from the file.

Print Employee Salary Slip:
  
  This feature too asks for the employee code; the employee code has been used to unlock or perform operations in many features of this payroll management system project in C++. This function lists all the months of the year, and asks for date, employee name, designation and grade from the user. To print the salary slip, the user further needs to provide information such as number of days worked in the month by the employee and the number of hours worked over time. The slip enlists basic salary, allowance, deductions and net salary of the employee.

Display Employee Record:

 Providing the employee code number, users can access all the provided information related to a particular employee via this function. The employee record information displayed are the ones provided while adding a new employee record.

Display List of Employees:

  This feature displays the record of all employees added in file. The records are displayed in a tabular pattern containing information such as code name of the employee, phone number, date of joining, designation, grade and salary.

# Contribute

Please feel free to add your own code, fix bugs or improve the docs.
