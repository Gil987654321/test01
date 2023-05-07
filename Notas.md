# Comandos.
    pip install -r requirements.txt
    pip3 freeze > requirements.txt
    gunicorn --worker-tmp-dir /dev/shm --config gunicorn_config.py app:app
