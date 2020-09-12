# MyResultPortal
sample website made using Python &amp; DJango to display the result of students
to run this project, you needto change following this.
1. create a virtual environment.
2. install dependencies using requirement.txt
3. select the database you want to link. 
4. edit the crediential of your database in setting.py file. 
5. after updating the database crediential you need to do the migration.
5(a) > python manage.py makemigrations
5(b) > Python manage.py migrate
6. run the project using python manage.py runserver
7. see the output on http://127.0.0.1:8000/
