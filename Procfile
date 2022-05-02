release: python mega_zord/manage.py migrate
web: gunicorn mega_zord.wsgi && celery -A mega_zord worker -l INFO 
