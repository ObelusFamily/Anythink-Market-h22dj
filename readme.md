# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps For First Setup

First You need to Install Docker.

after Installation, you can verify it the docker is currently running on your system via 

docker -v

you will also get version of docker-compose installed as well to verify it run this command:

docker-compose -v

then in the Repository folder run:

docker-compose up

that's it for the first step you can verify it by navigating to this url if the backend is working

http://localhost:3000/api/ping

you can  check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on:

http://localhost:3001/register

Create one (choose a cool nickname and everything)