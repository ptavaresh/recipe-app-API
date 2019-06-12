# recipe-app-API

Please install Python 3.6 or above after that create and set up the virtual environment or install directly the dependencies available in the requirements.txt file using below command.
# to create a Virtual environment named recipe on windows.
Open the CMD and run the below comand
python3 -m venv recipe

# to set up the virtual env on windows.
Open the CMD and run the below comand
recipe\Scripts\activate

pip install -r requirements.txt

# docker commands
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
