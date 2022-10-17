# How to run
1. Run `docker-compose up`
2. Open a new terminal and run `docker exec -it django-docker_web_1 bash`
3. Inside the bash, run `python manage.py makemigrations`, then run `python manage.py migrate`
4. To create a new user, run `python manage.py createsuperuser <username>`

# About the app
You can visit the following urls:
1. [http://localhost:8000/snippets/](http://localhost:8000/snippets/)
This will show all the snippets. 

2. [http://localhost:8000/snippets/1/](http://localhost:8000/snippets/1/)
This will show the specific snippet according to its id. Only the owner of the snippet can edit his snippet.

3. [http://localhost:8000/users/](http://localhost:8000/users/)
This will show all the users.
