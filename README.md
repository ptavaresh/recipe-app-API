# recipe-app-API

docker-compose run app sh -c "python manage.py test"

# API endpoints

token [POST]
http://127.0.0.1:8000/api/user/token/

me [PUT, PATCH]
http://127.0.0.1:8000/api/user/me/

create user [POST]
http://127.0.0.1:8000/api/user/create/

list recipe's endpoints [GET]
http://127.0.0.1:8000/api/recipe/

Tags [GET, POST]
http://127.0.0.1:8000/api/recipe/tags/

Ingredients [GET, POST]
http://127.0.0.1:8000/api/recipe/Ingredients/

Recipe [POST]
http://127.0.0.1:8000/api/recipe/{id}/upload-image/