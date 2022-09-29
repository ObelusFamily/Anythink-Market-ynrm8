# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install [Docker](https://docs.docker.com/get-docker/) on your machine.

Clone this repo and run `docker-compose up`

Test environment is running the backend properly by navigating to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) on your web browser.

Test environment is running the frontend properly by navigating to [http://localhost:3001/register](http://localhost:3001/register) on your web browser.
