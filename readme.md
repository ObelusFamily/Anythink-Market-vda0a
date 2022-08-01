# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install Docker for your operating system.

2. Verify if docker is ready by running the following commands in your terminal:

   "docker -v" and "docker-compose -v"

3. Then run "docker-compose up" from the project root directory to load Anythink's frontend and backend.

4. If Docker is working correctly, the backend should be running and able to connect to your local database. To test this go to http://localhost:3000/api/ping on your browser.

5. If the backend is up and running check the frontend and make sure it’s connected to the backend. To check this go to http://localhost:3001/register and create a new user.
