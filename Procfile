release: python manage.py migrate
web: gunicorn config.wsgi:application
worker: celery worker --app=my_sandbox.taskapp --loglevel=info
