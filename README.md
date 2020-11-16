# There are three main packages we need for our project:

Flask
Flask-Login: to handle the user sessions after authentication
Flask-SQLAlchemy: to represent the user model and interface with our database

## create a virtual env 
python3 -m venv env

```
>>> from project import db, create_app, models
>>> db.create_all(app=create_app())
```