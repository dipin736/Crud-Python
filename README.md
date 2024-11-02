# Employee Management API

A simple REST API to manage employee records, including creating, reading, updating, and deleting employees, with pagination and filtering support.

# Features
Create Employee: Add new employees with unique emails.

List Employees: View all employees with pagination, and filter by department or role.

Retrieve Employee: Get details of a single employee by ID.

Update Employee: Modify an employee’s details.

Delete Employee: Remove an employee from the database.


# API Endpoints
Here are the endpoints available in this API:

# Authentication
Get Token: POST https://crud-python-hcao.onrender.com/api/token/

Refresh Token: POST https://crud-python-hcao.onrender.com/api/token/refresh/
# Employees
List & Create Employee: GET, POST  https://crud-python-hcao.onrender.com/api/employees/

Retrieve, Update & Delete Employee: GET, PUT, DELETE  https://crud-python-hcao.onrender.com/api/employees/<int:pk>/

