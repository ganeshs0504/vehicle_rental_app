ECS-14-Team-Project
-------------------------
Project Presentation Link: https://gla-my.sharepoint.com/:v:/g/personal/2935548s_student_gla_ac_uk/EUeEowR8qgVFoFzLpzlDNiQBK7AgdD1ZO4rK8qnkSWOK5A?e=g9sIuu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19
-------------------------

Application startup guide
For the application environment to be initialised properly, make sure the following requirements are satisfied.

Install python (preferably python3) https://www.python.org/downloads/

Make sure the environment variables are set for Python during the installation.

The application requires an additional libraries to be installed on the device, namely pandas, matplotlib and Argon2.

To download these dependencies, simply enter the following commands in the terminal one by one.

1. pip install jupyter # For Argon2 and its dependencies
2. pip install pandas
3. pip install matplotlib


If you are running it for the first time, you must run the test.py file first to create the database and set it up with default data

Starting the application afterward is very simple. Running the mainApp.py file in the outermost folder will open the main window, and from then on, the user is free to use the functions described in the report.

Application Flow for different users:
Customer
--------
- Login with the credentials given below.
- Click the user icon to add money to wallet.
- Select the city and the vehice to be rented from the list.
- Click rent to begin the rent.
- In the next window end rental and mark or unmark te vehicle as damaged and finally end the rental.

Operator
--------
- Login as operator with the given credentials.
- Click buttons associated to actions like recharge and repair to perform the specified actions.
- Click add vehicle to add a new vehicle to the fleet.

Manager
-------
- Login as manager with the given credentials.
- Click the appropriate report function to display the report in the window.
- Click download button to download the displayed report.

Test Data
To be able to explore all the core functionalities fully, here are the log-in credentials for each type of user with pre-defined randomized data for visualization

Customer
Email: user1@ecs14.com
Password: password
--------
Operator
Email: op1@ecs14.com
Password: password
--------
Manager
Email: manager1@ecs14.com
Password: password