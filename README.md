# Gaijin Give aways

Known bugs: 
* Paypal payment system has small bugs

## Summary
This is a Web page that uses the flask framework to mix python, css, html and Javascript to form a fuctional web application. The web page uses an sql server to process loging in and out of an account and signup, as well as storing tickets purchased, and drawwing a winner.
Payments are processed via paypal 

## programming language uses
* HTML: templates for the gui
* CSS: Styling for the html gui
* Python: basic logic and SQL conection and utilization
* SQL: storing user information for account services, and ticket processes

## SQL structure
<b>User table:</b>
- id int prim key
- username varchar
- email varchar
- phone varchar

<b>Tickets table: </b>
- tid int prim key
- id foreign key

