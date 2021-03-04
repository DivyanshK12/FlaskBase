# Description
This is a basic template for a flask app.

# Initial Steps
* Create a virtual environment using:
``` python -m venv venv\
```

* In the environment install dependencies from requirements.txt
* Create a migration using the following commands :

* python manage.py db init
* python manage.py db migrate
* python manage.py db upgrade

# Important steps while deploying
* In the migrations/ folder, put an empty .keep file in versions/ if initally there is no migration as the folder would then not be created
* Change secret key in config.py