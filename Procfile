web: gunicorn instawork_assignment.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
python manage.py migrate