# Price-Tracker-Application
Discount Tracker app with Python/Django

## Getting Started

This tutorial works on **Python 3+** and Django 2+.

Install dependencies:

```
python3 -m pip3 install -r requirements.txt
```
start Celery worker:

```
celery -A pricetracker worker -l info

```
and run following commands:

```
python3 manage.py makemigrations tracker
python3 manage.py migrate
python3 manage.py runserver
```


## Mine

A discount tracking application with django, celery and others

- Following tutorial from this link - https://dev.to/coderasha/price-tracker-application-with-django-track-discounts-889

- Always make sure to freeze the environment `pip freeze > requirements.txt`

- If there is no virtual enviroment exists then make `pip install -r requirements.txt`

- RabbitMQ location on my pc - `C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.3\sbin`

- RabbitMQ management enabling command - `rabbitmq-plugins enable rabbitmq_management`

- To check everything as expected open any browser and access the http://localhost:15672 URL then you would see the below RabbitMQ login page.

- Default credentials are: **User Name**: guest **Password**: guest