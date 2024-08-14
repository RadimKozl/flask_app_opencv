# **flask_app_opencv**

<img src="notebooks/img/OpenCV_logo.png" alt="OpenCV logo" style="width: 200px;"/>

## ***Assignment of [OpenCV University course](https://opencv.org/university/computer-vision-and-deep-learning-applications/)* : Deploy Web App**


<img src="notebooks/img/SVmetalLogo.png" alt="SVmetal logo" style="width: 200px;"/>

>Note: ### *This project was created with the support of [SVmetal spol. sr. o.](https://www.svmetal.cz/cs)*


## ***Development***:
For Unix OS!!!

```cmd
flask --app web_app run
```
Necessary use Unix OS for gunicorn!!!

> pip install gunicorn

```cmd
gunicorn --config gunicorn_config.py web_app:app
```

For window use waitress!!!

> pip install waitress

## ***Deploy by Koyeb***

[Documentation](https://github.com/RadimKozl/flask_app_opencv/blob/main/notebooks/Introduce_Koyed.md)