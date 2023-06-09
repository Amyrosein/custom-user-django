# custom-user-django
Custom User Model App for django Projects ( Email required user model )

## Usage

1. first clone this app to your django project
2. then go to settings.py of your project and add this line to the INSTALLED_APPS list :
```python
INSTALLED_APPS = [
    # your apps
    'home.apps.HomeConfig',
]
```
3. then add this line in the bottom of your settings.py file:
```python
 AUTH_USER_MODEL = "accounts.User"
```

4. Its done now make migration and migrate and create super user and finally run server 
