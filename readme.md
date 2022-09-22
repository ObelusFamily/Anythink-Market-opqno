# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Install ([Docker](https://docs.docker.com/get-docker/)).

2. Make sure docker is up and running, by running `docker -v` and `docker-compose -v`.

3. Then run `docker-compose up` in the root directory of your project.

4. Once that's done, make sure the backend is running by going to http://localhost:3000/api/ping. If everything works as intended, you should be able to create a new user by following the form on http://localhost:3001/register.

5. Profit.
