# SchoolManagement
To start the application on our local server, simply run this command using the VS code command line (or any command line).

```bash

Create Virtual Environment:
--------------------------------
python -m pip install virtualenv
python -m venv venv
venv\Scripts\activate

Now run the commands:
---------------------
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python mangae.py runserver
```
