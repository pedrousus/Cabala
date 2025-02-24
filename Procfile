web: gunicorn traslateapi.wsgi --log file -
release: python manage.py collectstatic --noinput
web: python manage.py migrate && gunicorn traslateapi.wsgi

