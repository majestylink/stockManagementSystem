release: cd vedez
release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input


web: gunicorn vedez.vedez.wsgi --log-file