# Django Commands
### Creating a new Django project
```
python manage.py startproject <project_name>        # if you add . at last it creates on dir or else it will create two 
```
### Creating a new app within a Django project
```
python manage.py startapp <app_name>
```
### Launching the development server for testing
```
python manage.py runserver
```
### Creating new database migration files
```
python manage.py makemigrations
```
### Applying database migrations 
```
python manage.py migrate
```
### Displaying a list of all the migrations for your project 
```
python manage.py showmigrations           #Displays a list of all the migrations for your project along with their applied or pending status
```
### Creating a superuser account for the Django admin 
```
python manage.py createsuperuser <user_name>
```
### To open python shell programmming
```
python manage.py shell
```
### Clearing all data from the database
```
python manage.py flush
```
### Creating an empty migration in a app
```
python manage.py makemigration <app_name> --empty    #this is used to execute raw sql code
```

