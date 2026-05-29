📘 Login System
==============================================

A beginner-friendly Python login system designed to demonstrate user authentication, input handling, conditional logic, and basic security concepts through a simple credential verification process.

----------
🎯 Purpose
----------

*    Demonstrate basic user authentication in Python

*    Master and acquire proficiency in using dictionaries and error handling
    
*    Understand real-world applications of dictionaries and error handling
    
-----------
🎯 Features
-----------

*  Accepts username and password input from the user
  
*  Stores credentials using a Python dictionary
  
*  Verifies login credentials using conditional statements
  
*  Prevents unauthorized access for invalid usernames
  
*  Displays an error message for incorrect passwords
  
*  Uses a while loop to repeatedly prompt the user until a successful login
  
*  Implements exception handling using try-except
  
*  Automatically opens a website after successful authentication
  
*  Uses string methods like .upper() for case-insensitive login checking

--------------------------
🚀 Concepts and principles used
--------------------------

### Receive user input:
The program uses the input function to obtain the user’s username and password for authentication and verification.

### Credential storage:
The valid usernames and passwords are stored using a Python dictionary, allowing the program to match login credentials efficiently.

### Authentication system:
The entered username and password are compared with the stored credentials to determine whether the user is authorized to access the system.

### Conditions:
If the entered username is not found in the stored credentials, the program denies unauthorized access. If the password is incorrect, the program displays an error message and prompts the user to try again.

### Loop system:
The while loop continuously runs the login process until the correct credentials are entered successfully.

### Exception handling:
The program uses try-except blocks to handle invalid input errors and prevent the program from crashing unexpectedly.

### Automatic website access:
After successful login verification, the program automatically opens a website using the webbrowser module.


--------------------------
🚀 Tools used
--------------------------
Python IDE used - PyCharm

--------------------------
🚀 New functions to learn:
--------------------------

* != mean 'not equal to.'

* To link the username and password, we used a dictionary (because it ensures only one password per user)
  The general form of a dictionary is: dictionary = {(key1, value1), (key2, value2), ......}
  
* In the code, we used:
  ```
             password == credentials[username]
  ```
  credentials[username] looks up the value (password) associated with the key (username)

* .strip() is used in Python to remove leading and trailing whitespace characters. It does not affect spaces inside the        string, but only at the beginning and the end.

* leading and trailing whitespace characters include spaces, tabs(/t) and newline characters(/n)
 It does not affect spaces inside the string, but only at the beginning and the end.

* There are two main variants of this method - .lstrip() and .rstrip()
 
----------
📘 How can it be improved in the future?
----------
### 🔐 Limit login attempts
   Allow only a fixed number of password attempts (example: 3 tries)
   Deny access after exceeding the limit
### 👁️ Hide password while typing
   Prevent the password from being visible during input
   Use the getpass module for secure password entry
### 🕒 Add loading/welcome effect
   Create a realistic login experience using delays
   Example: “Logging in...” animation using the time module
### 📅 Show login date and time
   Display the current login timestamp after successful authentication
   Use the datetime module
### 🔑 Password strength checker
   Validate password quality using conditions
   Check for:
   1. Minimum length
   2. Uppercase/lowercase letters
   3. Numbers and symbols
### 👤 User registration system
   Allow users to create new accounts
   Store usernames and passwords dynamically
### 📂 Save credentials to a file
   Store login information in a text file
   Preserve user data even after the program closes
### 🚫 Temporary account lock system
   Lock login attempts temporarily after repeated failures
   Example: wait 30 seconds before retrying
### 🎨 Create a menu system
   Add options such as:
   1. Login
   2. Register
   3. Exit
   Improves program structure and navigation
### 🌐 Add role-based access
   Assign different roles such as:
   1. Admin
   2. User
   3. Guest
   Provide different permissions/features for each role


----------
