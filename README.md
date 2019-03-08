# Django-Registration
When we sign up on website its send a email for confirmation to active an account. Here i will show you how to send a confirmation email when someone register on your web app that deploy on Django.

1) Downlaod Web application Django-Registration.zip file
2) Create Virtual environment : virtualenv env
3) Activate env : for linux: source env/bin/activate
                  for windows: env/Scripts/Activate
4) cd Django-Registration folder
5) pip install -r requirements.txt
6) python manage.py makemigrations app
7) python manage.py migrate
8) python manage.py runserver
9) Open http://127.0.0.1:8000

![django_1](https://user-images.githubusercontent.com/14355490/54023490-18aa1400-41bb-11e9-98cb-ff55055b5e35.png)
![django_2](https://user-images.githubusercontent.com/14355490/54023492-19db4100-41bb-11e9-89f5-dd18c7074f6c.png)

## Configure settings:
Firstly we configure email host server in settings.py for sending confirmation email.

email_reg/settings.py

1) EMAIL_HOST_USER = 'youremail@gmail.com'
2) EMAIL_HOST_PASSWORD = 'yourpassword'

## Credits:
https://medium.com/@frfahim/django-registration-with-confirmation-email-bb5da011e4ef
