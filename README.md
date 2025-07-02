#  Online Course Portal

A full-featured web application built with Django that allows users to browse, enroll in, and learn from online courses. Admins can manage course content, users, and track enrollments with ease.

##  Features

-  User registration and login
-  Browse and view course details
-  Enroll in courses
-  Add video lectures and materials
-  Admin dashboard to manage courses and users
-  Optional discussion or comment sections

##  Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Backend:** Python (Django Framework)
- **Database:** SQLite 

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-course-portal.git
   cd online-course-portal
2. Create and activate a virtual environment:
   
python -m venv venv
source venv\Scripts\activate

4. Install dependencies:
   
pip install -r requirements.txt

6. Apply migrations:
   
python manage.py migrate

8. Create a superuser (admin):
   
python manage.py createsuperuser

6.Run the server:

python manage.py runserver

