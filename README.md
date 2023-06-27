# 2.-Working-with-forms-files-and-functions

Task:
Create three files named index.php, addUser.php and showUsers.php. All files must be in the same folder.
The index.php file should contain a menu with two items Add and Show. The first menu item should activate the addUser.php page, the second should activate the showUsers.php page.
The addUser.php file must contain a user registration form. The form can be arbitrary, but it must contain fields for the username, password and e-mail address of the user. In addition to these fields, the form, at your discretion, may contain other fields.
After filling out the form and pressing the submit button, information about the new user should be written to a file called users.txt. In this file, information about each user must be written on a new line. It is necessary to provide some kind of separator between the login, password, address and, possibly, other fields in this file. The user record might look like this:
Mary: 12345M: adminmary@gmail.com
Archer: archer555: archerboy@yahoo.com
Write to a file only if the login added to the form does not yet exist in the file. If the user with the login added to the form already exists, you must issue a message about this and do not write to the file.
The showUsers.php file should output to the browser in the form of a table (in the tag) a list of all users from the users.txt file.
Write to the file as a function, to which to pass an array with data about the user.
On the index.php page, you need to display the current number of users in the users.txt file.
