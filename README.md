# Console-based User Management Program
This program is a console-based Python program that allows users to add, store, and display information about users in an Excel file. It provides a simple interface where users can enter new details, view stored data, or exit the program. The information is saved in an Excel file called data_of_users.xlsx, which is created automatically if it doesn’t exist.

## Steps Performed by the Program
Initialize the Excel File (if needed):
The program checks for the existence of data_of_users.xlsx.
If the file doesn’t exist, it creates it and adds headers (Name, Email, and Phone Number).

Display Options to the User:
The main menu presents three options:
1: Add a user.
2: Display all users.
3: Exit the program.

- Add User (Option 1):
If the user selects option 1, they are prompted to enter:
Name, Email, Phone Number.
This information is then saved as a new row in the data_of_users.xlsx file.

- Display Users (Option 2):
If the user selects option 2, the program reads data from users_data.xlsx and displays each user's information in a readable format.

- Exit the Program (Option 3):
Selecting option 3 closes the program.

Handle Invalid Inputs:
If the user enters an invalid option, the program prompts them to try again and redisplays the main menu.

This process allows users to manage user data easily through a simple, interactive command-line interface.
