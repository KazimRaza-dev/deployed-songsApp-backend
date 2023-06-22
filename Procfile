web: gunicorn songs_app_backend.wsgi --log-file -
worker: celery -A songs_app_backend worker --loglevel=info