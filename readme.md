# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Step 1) Clone this repository from https://github.com/ObelusFamily/Anythink-Market-55ppw.git
Step 2) To run please install docker on your system from https://docs.docker.com/get-docker/
Step 3) It'll take some time to install depends on your system configuration, once install using command "docker -v" and "docker-compose -v" and see whether getting version details or not.
Step 4) Now go to root directory of project and run "docker-compose up" and then verify by visiting to http://localhost:3000/api/ping
Step 5) Learn with fun.