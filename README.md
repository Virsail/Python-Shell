# Python Shell
## Author

[Virsail](https://github.com/Virsail)

## Description

This project is a python application that manages login and signup credentials of a person for various accounts i.e. username and passwords for each account. It also stores the passwords and generates a unique password for a user if they do not want to generate new passwords by themselves.User can also copy credentials to clipboard.

## Screenshot

<img src="https://raw.githubusercontent.com/Virsail/Python-Shell/master/image/screenshot1.png" width="900px" height="440px">

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
| User Stores a new credential in the application| User Enters ```CC```|Enter Account, username, password<br>choose ```tp``` to enter your password or ```gp``` for the application to generate a password for you |
|Display all stored credentials |User Enters ```DC```|A list of all credentials that has been stored or ```You don't have any credentials saved yet``` |
|Find a stored credential based on account name|User Enters ```FC```| Enter the Account Name you want to search for and returns the account details|
|Delete an existing credential that you don't want anymore|User Enters ```D```|Enter the account name of the Credentials you want to delete and returns true if the account has been deleted and false if the account doesn't exixt|
|Exit the application|User Enters ```EX```| The application exits|

## Technologies Used

* python3.8


## Contact Information 
 [virsaileric@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2019 **Owiti Charles**
