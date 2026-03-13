## Team Contributions
* Margie - Employee details and login/logout system
   * Handled the login logic for both employee and payroll staff users.
   * Managed the employee menu and the display of employee details.
* Julius - Get employee info
   * Focused on extracting employee information from the Employee Details.csv file.
   * Worked on parsing employee data like name, birthday, and hourly rate.
   * Assisted in linking employee data to the attendance records.
* Gibby - Payroll calculation
   * Responsible for the logic in computing gross and net salaries, including deductions (SSS, PhilHealth, Pag-IBIG, tax).
   * Implemented the cutoff splits (1st–15th and 16th–end of month).
   * Worked on the computeHours() method and the display of payroll summaries.
* Jana - Minor adjustments
   * Made refinements to the code for better functionality and readability.
   * Helped small fixes across the system.

# MotorPH Basic Payroll System 

The Basic Payroll MotorPH system is a console-based Java application that simulates a simple payroll system for a company called MotorPH. It allows two types of users to log in:
* Employee Users – Can view their personal details by entering their employee number.
* Payroll Staff Users – Can process payroll for one or all employees.

### How It Works:
### 1. Login System
* Users are prompted to enter a username and password.
* Valid credentials:
   * Employee: employee / 12345
   * Payroll Staff: payroll_staff / 12345
### 2. Employee Menu
* Employees can enter their employee number to view their personal information (e.g., employee number, name, birthday) from the Employee Details.csv file.
### 3. Payroll Staff Menu
* Payroll staff can:
   * Process payroll for a single employee by entering their employee number.
   * Process payroll for all employees by looping through the employee list.
* For each employee, the system:
   * Reads attendance records from Attendance Record.csv.
   * Computes total hours worked per cutoff (1st–15th and 16th–end of month).
   * Calculates gross salary based on hourly rate.
   * Applies deductions (SSS, PhilHealth, Pag-IBIG, tax) for the second cutoff only.
   * Displays a detailed payroll summary per month (June to December 2024).
### 4. Attendance Computation
* Login and logout times are parsed and compared.
* A grace period until 8:10 AM is considered; late logins reduce worked hours.
* Maximum of 8 hours per day is applied.

Project Plan Link
* https://docs.google.com/spreadsheets/d/1dBRgeTXiUNJuw5zbtHSljKCA9ZgDH7hiGJl_bFZogwI/edit?usp=sharing
<br> 


