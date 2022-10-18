This is a simple webpage project representing webshop using:
- Python, Django framework, Bootstrap framework and HTML.
- Django framework (https://www.djangoproject.com)
- Bootstrap framework (https://getbootstrap.com) (Card component, Navbar component)
- database: sqlite3 (useful software to see database: https://sqlitebrowser.org)

Prerequisite is to install django via terminal command:
>pip3 install django

We need to create a project with django. This command will create a file named 'manage.py' and also a folder named "pyshop" with few python files in it:
>django-admin startproject pyshop .

Next step is to run django server with this command:
>python3 manage.py runserver

Then, open a new terminal window and run this command:
>python3 manage.py startapp products

See products list:
http://127.0.0.1:8000/products

admin screen:
http://127.0.0.1:8000/admin

Username/password: admin/1234

