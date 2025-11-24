release: cd application && python manage.py collectstatic --noinput
web: cd application && gunicorn application.wsgi:application --bind 0.0.0.0:$PORT --log-file -
