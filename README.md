# PyShop
Django online shopping site
#### 1st Step:
First clone the repository in your local machine
#### 2nd Step:
##### Django Project Management Commands
This repository contains a Django-based project named **PyShop**. Below are some commonly used management commands that can be executed using the __manage.py__ script.
```
python manage.py makemigrations
```
This command creates new database migration files based on the changes made to the project's models. 
It examines the models defined in the project and generates the necessary SQL statements to update the database schema.
```bash
python manage.py migrate
```
This command applies the pending database migrations to the database, updating the database schema to match the changes made to the models.
```python
python manage.py createsuperuser
```
This command creates a new Django superuser account. Superusers have access to the Django admin interface and can perform administrative tasks 
such as managing users and groups, editing site content, and managing application settings.
```
python manage.py runserver
```
This command starts the Django development server, allowing you to view and test the project in a local environment. 
By default, the server runs on port 8000, and you can access the server by opening a web browser and navigating to http://localhost:8000/.
<br>
Note that these are just a few of the many management commands available in Django. 
By using these commands, you can easily manage your project's database, user accounts, and server configuration, among other tasks.

#### 3rd Step:
* Now go to http://127.0.0.1:8000/admin address and log in with your superuser ID and password.
* Add some product details with images. Just copy the copyright-free Image URL and paste it into the Image URL field
* Go to http://127.0.0.1:8000/products to check the products
