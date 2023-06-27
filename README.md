# Human Resources: Terminal Application
### GitHub Repository: [github.com/tmarentes/terminal-app](https://github.com/TMarentes/terminal-app) 
<br>

## Contents
[Styling Convention](https://github.com/TMarentes/terminal-app#styling-convention)

[Application Features](https://github.com/TMarentes/terminal-app#features)

[Help Documentation](https://github.com/TMarentes/terminal-app#help-documentation)

[Implementation Plan](https://github.com/TMarentes/terminal-app#impmlementation-plan)



<br>

## Styling Convention
PEP8 Styling Convention
https://peps.python.org/pep-0008/

<br>

## Features
### Search by name or email
This feature will allow users of the application to search for employees in the human resources application. Users can search by name, where the name must be an exact match, or users can search by email. The application can use a for loop to find matching employees.

![Search by name or email](docs/employee_search.png)

<br>

### View all employees
Users will have the option to view all of the employees within the Employee class. Employees will be listed as one per line, with commas separating each attribute.

![View all employees](docs/list_all.png)

<br>

### Export employees to csv
This feature will allow users of the application to export employees into a csv file. This will be done using the csv python module and file handling. Users will be prompted after searching for employees to ask whether they would like to export their search as a csv.

![Export employees to csv](docs/export_csv.png)

<br>

### Add & delete employees
Adding and deleting employees is vital in a human resources management system. Users will be able to add new employees to the database, as well as delete existing employees by name or email.

![Add & delete employees](docs/employee_delete.png)

<br>

### Edit existing employee
Users will be able to edit existing employees within the database. Users could search by name or email to find the employee they wish to edit.

![Edit existing employee](docs/edit_options.png)

<br>


## Help Documentation

### Dependencies

<b>Python3: </b> [Python.org](https://www.python.org/downloads/)

<b>Bash: </b> [Windows](https://hackernoon.com/how-to-install-bash-on-windows-10-lqb73yj3)  / [Mac](https://scriptingosx.com/2019/02/install-bash-5-on-macos/)


### System Requirements
This application runs on Windows, Mac or Linux.

### Installation
1. Download the contents of the "src" folder in the GitHub repository
2. Execute the "script.sh" file to run the application
3. Users without Python3 installed will be prompted to install Python3

### Commands

![Welcome Screen](docs/welcome_screen.png)

Upon running the application, users are first greeted with a welcome screen. Users can enter anything to continue, or can simply press enter.


<b>Main Menu Interface</b>
The main menu interface presents 5 options to the user. 

![Main Menu](docs/main_menu.png)

- Entering "1" will open the Search interface
- Entering "2" will open the Edit interface
- Entering "3" will prompt users to add a new employee
- Entering "4" will prompt users to delete an employee
- Entering anything else will exit the application


- enter to continue
- number select, 1 2 3 4. anything else to exit
<b>Search Employees Menu</b>
<b>Edit Employees Menu</b>
<b>Add Employee Menu</b>
<b>Delete Employee Menu</b>


<br> 


## Implementation Plan
### Initial Steps
In the early stages of developing a terminal application in Python, the first steps are creating a GitHub repository and establishing a connection to Git. This enables version control as the project progresses.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|Create github repository|  24/06/23      |  ✅  | 
|Connect git|  24/06/23      |  ✅  | 
|Create assignment directories|  25/06/23      |  ✅  | 
|Write Pseudocode|  25/06/23      |  ✅  | 
|Create python files|  25/06/23      |  ✅  | 
|Setup shell script|  26/06/23      |  ✅  | 
|Create python classes| 26/06/23       |  ✅  | 

![Trello Board](docs/initial_steps.png)

<br>

### Interface
An interface will be created with an interface class with multi-line print statements as functions.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create interfaces class|  27/06/23      |  ✅  | 
|write interface print function|  27/06/23      |   ✅ | 
|add interface function to main.py|  28/06/23      |  ✅  | 
|initialise employees class|  28/06/23      |  ✅  | 

![Trello Board](docs/interfaces.png)

<br>

### Search by name or email
The search functionality will use a Search class with functions that access the Employee class.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create search menu interface|  28/06/23      |  ✅  | 
|initialise search class|  28/06/23      |  ✅  | 
|write search by name function|  29/06/23      |  ✅  | 
|write search by email function|  29/06/23      |  ✅  | 
|add search class to main.py|  29/06/23      |  ✅  | 
|run pytests on search functions|  05/07/23      |    | 

![Trello Board](docs/search.png)

<br>

### View all employees
To view all employees, a method in the Search class accesses the entire Employee class.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create view all function in search class|  30/06/23      |  ✅  | 
|run pytests on view all function| 05/07/23     |    | 



<br>

### Add & delete employees
To add and delete employees, methods are used in the Employee class.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create add new employee interface|  01/07/23      |  ✅  | 
|create delete employee interface| 01/07/23     |  ✅  | 
|create user input for new employee|  01/07/23      |  ✅  | 
|add employee class method to add new employee|  01/07/23      |  ✅  | 
|add employee class method to remove employee|  01/07/23      |  ✅  | 

![Trello Board](docs/add-delete.png)

<br>

### Edit existing employee
To edit an existing employee, the user first must search for the employee, then will be prompted with inputs for the new information.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create edit employee interface|  02/07/23      |  ✅  | 
|create user input for new data| 02/07/23     |  ✅  | 
|add employee class method to edit employee|  02/07/23      |  ✅  | 

<br>

### Export employees to csv
Employees are exported using the csv module in python.

|Task|Deadline|Status|
|----------------|:------:|:----:|
|create export interface|  03/07/23      |  ✅  | 
|initialise export class| 03/07/23     |  ✅  | 
|write export all to csv function|  03/07/23      |  ✅  | 
|write export by name|  03/07/23      |  ✅  | 
|write export by email|  03/07/23      |  ✅  | 

![Trello Board](docs/export.png)
