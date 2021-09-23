release: python booktook/manage.py makemigrations --no-input
release: python booktook/manage.py migrate --no-input
release: python booktook/manage.py collectstatic --noinput
web: gunicorn booktook.wsgi