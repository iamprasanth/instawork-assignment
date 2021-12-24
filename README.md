# Instawork Django Assignment
A simple web application developed in Django for managing team members. Functionalities include creating, listing, editing and deleting members.

The application has been deployed in Heroku: https://instawork-asssignment-prasanth.herokuapp.com/

Database of choice is SQLite. Frontend is developed using plain HTML & CSS.

## Testing the app using docker

For ease of testing the project, I have created a docker image of the latest version of the application.
Please follow the below commands for viewing the app in a docker container.




```
docker pull prasanth1996/instawork_assignment:latest

docker run -p 8888:80 prasanth1996/instawork_assignment:latest
```


## License

This Instawork django assignment app is open-sourced software licensed under the MIT license
