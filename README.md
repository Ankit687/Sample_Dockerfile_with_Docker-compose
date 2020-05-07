# Sample_Dockerfile_with_Docker-compose
create a Django docker container using docker-compose

# first make user to root access
$ sudo chown -R $USER:$USER .

# now run the container
$ sudo docker-compose up

# if it is not working than also run this command
$ sudo docker-compose run web django-admin startproject Watcix_Backend . <br/>
$ sudo docker exec watcix_web_1 python manage.py startapp Backend
