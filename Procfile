web: gunicorn manage:app
heroku ps:scale web=1
release: python manage.py db upgrade

