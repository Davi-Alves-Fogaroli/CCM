release: python mega_zord/manage.py migrate
web: gunicorn mega_zord.wsgi && celery -A celery worker -l INFO 
