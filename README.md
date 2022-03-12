# python-url-shortener
This simple python url shortener project uses Flask, sqlite, and gunicorn.

Install with
```
pip install -r requirements.txt
```

Edit gunicorn.conf.py to reflect the port on which you wish to run the application.  

Run with
```
gunicorn3 -c gunicorn.conf.py wsgi:app
```
