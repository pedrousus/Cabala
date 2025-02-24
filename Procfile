release: python manage.py collectstatic --noinput
web: gunicorn traslateapi.wsgi:application --bind 0.0.0.0:8000
