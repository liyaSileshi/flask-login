# There are three main packages we need for our project:

Flask
Flask-Login: to handle the user sessions after authentication
Flask-SQLAlchemy: to represent the user model and interface with our database

# To start the app
 
## create a virtual env 
```python3 -m venv env```

## activate your virtual env
``` source env/bin/activate```

## install the requirements
```pip3 install -r requirements.txt```

## run the app using this command
In a terminal, you can set the FLASK_APP and FLASK_DEBUG values:
```
export FLASK_APP=project
export FLASK_DEBUG=1
```

```
>>> from project import db, create_app, models
>>> db.create_all(app=create_app())
```
