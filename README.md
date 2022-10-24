# auth-email-django
little script to User login with email or username and password.

**Attention** 
This project need startproject django and start your app to login

## First step
How was said above need startproject django.

## Second step
This stage your need to set up in app 'base' at file settings.py this command.

```
AUTHENTICATION_BACKENDS = [
    'core.base.auth.Email_OR_Username'
]
```

## Third step
In your app that you to set up login.
1. Create file name as auth.py, but this name can be as want.
2. Settings in your file this script above 
``` auth.py ```