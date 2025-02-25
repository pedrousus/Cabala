release: |
  python manage.py migrate
  python manage.py makemigrations
  python manage.py collectstatic --noinput
web: gunicorn traslateapi.wsgi:app --bind 0.0.0.0:$PORT
