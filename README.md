# flask_app_opencv
Assignment: Deploy Web App

Nessesary use Unix OS!!!

***Development***:

```cmd
flask --app opencv_web_app run
```
Necessary use Unix OS for gunicorn!!!

> pip install gunicorn

```cmd
gunicorn --config gunicorn_config.py opencv_web_app:app
```

For window use waitress!!!

> pip install waitress

```cmd

```