# Django-Registration
When we sign up on website its send a email for confirmation to active an account. Here i will show you how to send a confirmation email when someone register on your web app that deploy on Django.

## Configure settings:
Firstly we configure email host server in settings.py for sending confirmation email.

email_reg/settings.py

1) EMAIL_HOST_USER = 'youremail@gmail.com'
2) EMAIL_HOST_PASSWORD = 'yourpassword'

## Credits:
https://medium.com/@frfahim/django-registration-with-confirmation-email-bb5da011e4ef
