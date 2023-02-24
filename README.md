# LoginSystem
A simple login website created with Bootstrap, PHP, and MySQL.

## Overview
### Registration
Users can create an account, inputting their first and last name, email, and password. Once submitted, a new `Users` instance is created in the `Users` database that is hosted on PHPMyAdmin.

### Logging In
Users who are currently registered in the database can use their email and password to log into the system.

### User Dashboard
Once logged in, the registered user will see a table of all users registered in the database; the user ID, first and last name, and email is displayed in this table. Users have the ability to delete a user (including themselves) and add a new user to the database.

#### Take a look at some [screenshots](screenshots/)!

## Improvements
### Security
Users can delete registered users, even if they themselves are not registered.

### More Functionality
Adding the ability to for registered users to edit data in the database (e.g. changing the first name).
