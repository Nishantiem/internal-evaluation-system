#Heading 1

Download the file.
extract the files to a new folder


#Heading 2

Installation and Configuration


Install Python 3.0 or above
Install MySQL 8.0 or above
Install pipenv 3.0 or above
Inside the virtual environment, run the following commands

pipenv install django
pipenv install mysqlclient

In case you are using VS code,
pipenv --venv
Copy the path. View--> Command Pallete--> select python interpreter
Enter the path and append '\Scripts\python' to it

Create a database named 'tcs_test' in mysql server
Give the permissions to the projects in the settings.py file in the DATABASES dictionary
Run: 'python manage.py migrate'
Run the SQL dumpfile to import the data



#heading 3
 To run the project, run following commands

 pipenv shell
 python manage.py runserver
 Use any standard browser and go to localhost:8000 to start the project



 