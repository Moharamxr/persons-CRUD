# persons-CRUD
My Node.js Application is a web application ,The API should allow users to perform CRUD to create and delete and read and update a list of items. The application is built using Node.js and is designed to be simple and easy to use.Each person object should have the following attributes:
• id
• name
• age
• gender
• email
Requirements To run the application, you will need the following:
Node.js v14 or later
A web browser

Usage
Creating
To create a new person, click on the "Add person" button on the homepage.

Reading 
To view a list of all persons, click on the "get all person" button on the homepage.

Updating 
To edit a person, click on the "update person" button .

Deleting
To delete a person, click on the "Delete" button .


Docker
To run the application in a Docker container, follow these steps:

-Build the Docker image: docker build -t moharamm/crud11 .

-Run the Docker container: docker run -p 3000:3000  moharamm/crud11

-The application will be available at http://localhost:3000. You can access the application in your web browser.

and you can pull it using : docker pull moharamm/crud11

the docker-compose.yml you can run it using : docker compose up
