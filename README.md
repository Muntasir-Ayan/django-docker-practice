# django-docker-practice

Mikegrations:

docker exec -it django_web python manage.py makemigrations polls

All migrations:
docker exec -it django_web python manage.py migrate

To see sql structure: 
docker exec -it django_web python manage.py sqlmigrate polls 0001
