# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
- Clone the repository using `git clone git@github.com:ObelusFamily/Anythink-Market-psyal.git`  
- After cloning, enter the project folder to setup the configurations
- Install docker `https://docs.docker.com/get-docker/`
- Check that the docker is installed properly with `docker -v` and `docker compose -v`
- Then, run `docker-compose up` from the project root directory to load Anythink's backend and frontend
- On your web browser, test the backend api using ` http://localhost:3000/api/ping`
- On your web browser, test the frontend api using `http://localhost:3001/register`
