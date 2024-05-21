# School Management System

## Project Overview
The **Online School Management System** is a comprehensive project developed using Python and the Django web framework. It serves as a fully functional School Management System designed to meet the needs of first-year and second-year IT students for their college projects. The system includes essential features for managing school records, ensuring that it mirrors real-life scenarios and is well-implemented.

## Features
- **Student Panel**
- **Teacher Panel**
- **Admin Panel**
- **Manage Requests**
- **Student Management**
- **Teacher Management**
- **Student Attendance Management**
- **View Fees and Pending Fees**
- **Publish Notice**

## Technologies Used
- **Programming Language**: Python
- **Designing**: HTML, CSS, JavaScript
- **Database**: SQLite
- **Framework**: Django, Django Rest Framework
- **IDE**: PyCharm, Visual Studio Code

To start the application on our local server, simply run this command using the VS Code command line (or any command line).

```bash
# Create Virtual Environment:
# --------------------------------
python -m pip install virtualenv
python -m venv venv
venv\Scripts\activate

# Now run the commands:
# ---------------------
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver









