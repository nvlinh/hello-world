1. command create app:
python manage.py startapp pages

Let’s review what each new pages app file does:

- admin.py is a configuration file for the built-in Django Admin app
- apps.py is a configuration file for the app itself
- migrations/ keeps track of any changes to our models.py file so our database and
  models.py stay in sync
- models.py is where we define our database models
  which Django automatically translates into database tables
- tests.py is for our app-specific tests
- views.py is where we handle the request/response logic for our web app

2. request/response cycle:
URL -> View -> Model (typically) -> Template