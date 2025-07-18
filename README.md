### Overview
The Employee Directory is a web application that allows users to manage and view employee information in an organized manner. It provides features for searching, filtering, sorting, and paginating employee data, as well as adding, editing, and deleting employee records.

### Features
  # Employee Management:

Add new employees with detailed information

Edit existing employee records

Delete employees from the directory

  # Viewing Options:

Search employees by name or email

Filter employees by first name, department, or role

Sort employees by first name or department (A-Z or Z-A)

Paginate results with customizable items per page (10, 25, 50, or 100)

  # Responsive Design:

Works on desktop and mobile devices

Clean, intuitive user interface

### Technologies Used
HTML5

CSS3 (with responsive design)

JavaScript (ES6)

No external dependencies (vanilla JS implementation)

### Installation
No installation is required to use this application. Simply open the index.html file in a modern web browser.

### Usage
  1. Viewing Employees:

The main grid displays all employees

Use the search bar to find specific employees

Apply filters using the filter sidebar

Sort employees using the dropdown menu

Navigate through pages using the pagination controls

  2. Adding an Employee:

Click the "Add Employee" button

Fill out the form with employee details

Click "Add" to submit the form

  3. Editing an Employee:

Click the "Edit" button on an employee card

Modify the information in the form

Click "Update" to save changes

  4. Deleting an Employee:

Click the "Delete" button on an employee card

Confirm the deletion in the popup dialog

### Data Structure
Employee records contain the following fields:

ID (auto-generated)

First Name

Last Name

Email

Department (HR, IT, Finance, Marketing, Operations, etc.)

Role (Manager, Developer, Analyst, etc.)

### Code Structure
index.html: Main HTML file with the application structure

styles/:

main.css: Primary styles for the application

responsive.css: Responsive design adjustments

scripts/app.js: Main JavaScript file containing all application logic

### API (for potential future expansion)
The application currently uses in-memory storage but is structured to easily connect to a backend API. The following functions could be adapted for API calls:

# javascript
addEmployee(employeeData)      // POST /employees
updateEmployee(id, employeeData) // PUT /employees/:id
deleteEmployee(id)            // DELETE /employees/:id

### Testing
The application includes form validation for:

Required fields

Minimum length for names

Valid email format

Unique email addresses

Required department and role selection

### Future Enhancements
Connect to a backend API for persistent storage

Add user authentication and authorization

Implement CSV import/export functionality

Add more detailed employee profiles with photos

Include advanced search and filtering options

Add department and role management#   e m p l o y e e - d i r e c t o r y  
 