# Cookie Stand

This app includes a frontend site that displays data about cookie stands. It also supports a Django REST Api. It
uses a PostgreSQL database supplied by ElephantSQL.

## Setup

- Requires a .env

## Tests

docker compose up

docker compose run web python3 manage.py test

## Run

docker compose up

Frontend: http://0.0.0.0:8000/

Backend: http://0.0.0.0:8000/api/v1/cookie_stand/

Admin: http://0.0.0.0:8000/admin/

