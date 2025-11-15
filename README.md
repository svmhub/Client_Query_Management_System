#####################################################################################################

                                    # Client Query Management System

#####################################################################################################

In this project, I have created a web application with the help of Streamlit package for creating a 
web application, SQLite pacakage like as a Database, Pandas and Numpy for handling the data, and
Matplotlib for visualizing the data in python(Ver. 3.10.5).

Here, I have given the procedures how I have created and completed this project.

This project contains the following steps to complete in a fantastic and easiest way.

    1.  Database and Tables creation
    2.  Main Page creation
    3.  Login Page creation
    4.  Client Page creation
    5.  Support Page creation

## Steps to developing the Client Query Management System:
==========================================================

## Step I:   Database and Tables Creation:-
------------------------------------------

    1. In this project , we should create a database and two tables has to be created in that. All the 
    and the flow of each and everything is available in the .ipynb file

    2. We need to create a database using sqlite in python.

    3. The procedures to implement this, I have given the file 1_Database_Creation.ipynb file. In that, 
    I have written all the codes related to the database and table creation including the required 
    pacakage installation of this.

    4. I would like to you go through that file line by line. It is very easy to understatnd and much 
    useful to paractice this to do.

## Step II: Main Page Creation:
------------------------------

    1. In this project, we used the streamlit package only for making the main page.

    2. Set the page configuration to display the content in the web page.

    3. Menubar has been used for the display the login and register menu in the main page.

    4. In 'Register' menu, we have kept a form to register the user in both the role is client and 
    support as well as 'Login' menu for the login the registered user.

    5. If you successfully logged in as a Client/Support, then it will switch you to the corressponding
    page.

## Step III: Login Page Creation:
--------------------------------

    1. A login page has been created separately to hande the database logic.

    2. In this page, I have imported the sqlite3, hashlib package.

    3. The hashlib password method has been implemented in thi file to convert the query page itself

    4. Also, we have kept two functions named as register_user and login_user. Both the function is 
    taking over of the back end(Database part) of the main page.

## Step IV: Client Page Creation:
--------------------------------

    1. The client page has been used the pacakages are streamlit, sqlite3, datetime.

    2. Declared the database file at the begining to use it in globe.

    3. A form has been implemented to submit the queries by the user.

    4. In the submission of the form, the form would be submitted to a function for the insertion of 
    the query to the queries table.

    5. The get_last_query_id function has implemented to find the last id from the table to generate 
    the new id.

    6. The generate_new_id function has been implemented to generate the new id for the inserting new
    queries in the queried table.

## Step V: Support Page(Dashboard) Creation:
-------------------------------------------

    1. In the support page, We have imported the following packages as follows,

            streamlit as steps
            matplotlib.pyplot as plty
            datetime
            pandas
            sqlite3

    2. Declared the database file at the begining to use it in globe.

    3. The hashlib password method has been implemented in thi file to convert the query page itself

    4. A function have implemented to get the total Queries 

    5. A function to get the current count of opened queries

    6. A function to get the current count of closed queries

    7. A function has been implemented to get all the queries.

    8. A close the query function has implemented to care the fetch the opened queries.

    9. we have displayed the queries like All, Opened, closed using filter

    10. We have created tabbed menu to have the extensive analysis of the datasets such as live intake, 
    monitoring and analysis.

******************************************************************************************************

Thus the project has completed successfully! Thank You

******************************************************************************************************
