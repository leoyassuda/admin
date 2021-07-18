# Admin

A micro-service in python using django and rabbitmq.

## Tech Stack

**Built-in:**

* [Python](https://www.python.org/)
* [Rabbit](https://www.rabbitmq.com/)
* [Docker](https://www.docker.com/)
* [Django](https://www.djangoproject.com/)
* [Mysql](https://www.mysql.com/)
* [Swagger-OpenApi](https://swagger.io/)

## Run Locally

Clone the project

```bash
  git clone https://github.com/leoyassuda/admin.git
```

Go to the project directory

```bash
  cd admin
```

Start using docker

```bash
  docker-compose up --build
```

Database migration

```bash
  docker-compose exec backend sh
  # python manage.py makemigrations
  # python manage.py makemigrate
```

Default port is 8000

> Example: http://localhost:8000/api/products

## Run Tests

TODO: Not implemented yet

## API Documentation

Open in browser - [swagger-ui](http://localhosr:8000/swagger)

### Authors

* **Leo Yassuda** - *Initial work* - [Admin](https://github.com/leoyassuda/admin) - Portfolio [leoyas.com](https://leoyas.com)