release: python manage.py migrate
web: gunicorn imageNetProj.wsgi 
web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker pythoncode:app
