# CS50 Final Project - simple email website

#### Description: A simple email website

The website allows you to send emails to another person registered on the website.

#### TECHNOLOGY USED:
- Node JS
- html
- sqlite3
- css
- other small libraries or packages

## HOW THE WEBPAGE WORKS:
The website is very simple to use. u can create your account with just 3 basic things:

- username(email)
- password
- confirmation password

once the account is created u will be redirected to the homepage of the website which will be initially blank due to no other emails.

#### WHAT CAN U DO HERE:
- inbox - once you log in the page u see is the inbox it includes all the mails sent to u

- compose -  now u can send a email to someone else with the help of the compose option.once the email is sent the page will be redirected to the sent history

- view email - if someone sends a mail to u , it will be displayed at ur homepage the email can be viewed with the view email option from where u will be redirected to the details of the email.

- reply to emails - a mail that has been sent to u can be viewed and replied immediately. the sender recipient and subject is auto completeed for the users better experience

### Sessions
The webpage uses sessions to confirm that user is registered.

### REFERENCE
This project is heavily referneced to the cs50 finance of pset 9. Many things have been reused to keep the porject simple and easy to use.
the helpers.py was very helpful for the faster completion of the project

### Database

Database stores all users and emails. There are 2 tables one which has all the registered users and the other one which includes all the emails sent using this website.

## Possible improvements

As all applications this one can also be improved. Possible improvements:

- The password strength should be measured and should be asked for better password if required
- Ability to change account details
- The option to delete the mails
- Mark the emails as important or spam
- check if the email the mail is being sent to exists or not

#### files
It uses 7 files for redirecting from one page to another

- apology - the website redirects to this file when a problem is caused while entering the details or the password is incorrect.

- compose - it is redirected to this when u are sending a mail to another user

- email - it is redirected to this when clicked on view mail for the details of the email

- login - the login page

- register - the register page

- reply - it is redirected tot his when clicked on the reply option while viewing a mail

- index - it is the homepage of the emails that u have recieved
