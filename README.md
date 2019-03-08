# Django-Registration

## Configure settings
Firstly we configure email host server in settings.py for sending confirmation email.

email_reg/settings.py

EMAIL_USE_TLS = True
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'yourpassword'
EMAIL_PORT = 587
