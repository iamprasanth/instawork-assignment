# Instawork Django Assignment
A simple web application developed in Django for managing team members. Functionalities include creating, listing, editing and deleting members.

The application has been deployed in Heroku: https://instawork-asssignment-prasanth.herokuapp.com/

Database of choice is SQLite. Frontend is developed using plain HTML & CSS.

## Sample screen

![alt text](https://github.com/iamprasanth/instawork-assignment/blob/main/memberapp/static/screens/screen1.png?raw=true)

![alt text](https://github.com/iamprasanth/instawork-assignment/blob/main/memberapp/static/screens/screen2.png?raw=true)

## Testing the app using docker





```
docker pull prasanth1996/instawork_assignment:latest

docker run -p 8888:80 prasanth1996/instawork_assignment:latest
```


