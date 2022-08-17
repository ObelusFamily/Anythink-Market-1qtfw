# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install [Docker](https://docs.docker.com/get-docker/).
- To check if Docker is working properly on your system check with :
    - ``` docker-compose -v``` :- This checks the docker-compose version 

- Go to the project root directory and then run ```docker-compose up``` to install and setup the dependencies.

- Setting up the backend:   
    - After all the dependencies have been installed, a Express server will start running with MongoDB database in the backend , you can verfiy all your project dependencies are working fine by doing 
    ``` curl http://localhost:3000/api/ping ``` and it should return a JSON response that everything should be working fine.

- Setting up the frontend:
    - Go to ``` http://localhost:3001/register``` while the server is running , and enter some data to check if the frontend is working properly and can talk with the server. 
