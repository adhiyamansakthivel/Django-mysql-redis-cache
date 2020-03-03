Install pipenv shell: pipenv shell
activate environment: pipenv shell
install requirements from requirements.txt: pip install -r requirements.txt
configure database(download fake records from google. In this project we used 1 million fake records to test.)
python manage.py migrate
open redis-server and redis-cli
run server: python manage.py runserver
open browser type http://localhost:8000/ in url you will get result.

after result load try to test in redis. 
open redis-cli 
keys *
db records will show.

This project for Learning purpose.