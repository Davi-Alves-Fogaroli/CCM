release: python mega_zord/manage.py migrate
web: gunicorn -w 2 ssp.wsgi & celery --app  ssp worker -l INFO 
