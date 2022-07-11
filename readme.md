# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. If not already done, install docker at [docker](https://docs.docker.com/get-docker/).
2. Check correct docker install with commands `docker - v` and `docker compose -v`
3. In project directory run `docker compose up`
4. Check success with http://localhost:3000/api/ping and creating a new user at http://localhost:3001/register
