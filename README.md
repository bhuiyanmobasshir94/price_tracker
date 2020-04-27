# price_tracker
A discount tracking application with django, celery and others

- Following tutorial from this link - https://dev.to/coderasha/price-tracker-application-with-django-track-discounts-889

- Always make sure to freeze the environment
`pip freeze > requirements.txt`
- If there is no virtual enviroment exists then make 
`pip install -r requirements.txt`

- RabbitMQ location on my pc - `C:\Program Files\RabbitMQ Server\rabbitmq_server-3.8.3\sbin`
- RabbitMQ management enabling command - `rabbitmq-plugins enable rabbitmq_management`
- To check everything as expected open any browser and access the http://localhost:15672 URL then you would see the below RabbitMQ login page.

- Default credentials are: **User Name**: `guest` **Password**: `guest`
