# Capstone III Task Manager

<br>

## The project description: 
The program was created to help a small business manage tasks assigned to each team member. This includes converting tasks and related data to and from text files, as well as creating, storing, displaying, and editing them.  

<br>

## Installation

To run this program, you must have Python 3, preferably, PyCharm installed on your computer and Notepad or other txt editor to open generated reports.

<br>

## Modules Used

The following modules are used in this project:

- `datetime` - The datetime module supplies classes for manipulating dates and times.

<br>

## Download the Source Code

You can download the source code from the GitHub repository.

<br>

## Run the Application

To run the application, navigate to the directory where you downloaded the source code and run the following command:
```
python task_manager.py

Log in to the programme using "admin" as your username and "adm1n" as your password. 
These specifics are also contained in the user.txt file.
```

<br>

## Menu

The user menu will be displayed once you have logged in. The user can enter the number of the option that they want to access from this menu.

```
Select one of the following options below:
    r -  Register a new user
    a -  Add a task
    va - View all tasks
    vm - View my tasks
    gr - Generate reports
    ds - Display stats
    e -  Exit
    :
 ```
 
 
- Register a new user - This option is only available to administrators. This option will prompt you for a username and password. 
                        If the entered username is already in use, the program will notify you and prompt you to try again. 
                        If your passwords do not match, you will see this message. 

- Add a new task - You can add new tasks using this option. The program will prompt you to enter the task title, description, 
                   username of the person you want to  assign the task to, and the task's deadline. 

- View all tasks - The application will display all tasks that have been generated.

- Vie all my tasks - The programme will display on the screen tasks assigned only to the logged-in user.

- Display stats - The programme will display all general information about tasks assigned to each registered user.

- Generate reports - This is a feature that only the admin user has access to. The goal of this feature is to create two files in the system that contain information about the users: `(user_overview.txt)` and `(task_overview.txt)`.

`(user_overview.txt)` - will display statistics for each user, including the number of tasks assigned to them, the number of tasks completed and uncompleted, and the number of tasks that are past due.

`(task_overview.txt)` - will display statistics about all tasks that have been registered in the system, including total tasks, tasks that have been completed and those that have not, as well as the number of tasks that are past due for all users combined. 
