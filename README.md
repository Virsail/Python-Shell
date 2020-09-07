# Python Shell
## Author

[Virsail](https://github.com/Virsail)

## Description

This project is a python application that manages login and signup credentials of a person for various accounts i.e. username and passwords for each account. It also stores the passwords and generates a unique password for a user if they do not want to generate new passwords by themselves.User can also copy credentials to clipboard.

## Screenshot

![Password-locker](image/ip2.png)

## User Story
The user would like to
* create an account for the application .
* Store my existing acounts login details for various accounts that i have registered for.
* Generate new password for an account that i haven't registered for and store it with the account name.   
* Delete stored account login details that i do now want anymore.
* Copy credentials to the clipboard


## Installation / Setup instruction

#### The application requires the following installations to operate 
* python3.8
* pyperclip
* pip

#### Cloning

* Open Terminal {Ctrl+Alt+T}

* git clone ```https://github.com/Virsail/Python-Shell.git```

* cd Password-locker

* code . or atom . based on the text editor you have.

### Running the Application
* To run the application, open the cloned file in terminal and run the following commands:

        $ chmod +x credential.py
        $ ./credential.py
* To run test for the application
        $ python3 user_test.py

## Behaviour Driven Development
| Given | When | Then |
| :---------------- | :---------------: | ------------------: |
| User Opens the application on the terminal | User runs the command ```$ ./credential.py```|Hello Welcome to your Accounts Password Locker Manager... <br>* CA ---  Create New Account * LI ---  Have An Account |
|User Selects  CA| User inputs username and password| Hello ```username```, Your account has been created succesfully! Your password is: ```password```|
|User Selects LI  | User Enters password and username he signed up with| Abbreviations menu to help you navigate through the application|
| User wants to Store new credentials in the application| User Enters ```CC```|Enter Account, username, password<br>choose ```tp``` to enter your password or ```gp``` for the application to generate a password for you |
|User wants to Display all stored credentials |User Enters ```DC```|A list of all credentials that has been stored or ```You don't have any credentials saved yet``` |
|User wants to Find a stored credential based on account name|User Enters ```FC```| Enter the Account Name you want to search for and returns the account details|
|User wants to Delete an existing credential that he doesn't want anymore|User Enters ```D```|Enter the account name of the Credentials you want to delete and returns true if the account has been deleted and false if the account doesn't exixt|
|User wants to Exit the application|User Enters ```EX```| The application exits|

## Technologies Used

* python3.8
## Contact Information 
Find me on @Ericmbagaya@gmail.com



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



Copyright (c) 2020 mbagaya
