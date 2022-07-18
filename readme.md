# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the git repository
```{bash}
git status
``` 
2. Install docker and docker-compose. Once they are installed, you should be able to check their version numbers like this.
```{bash}
$ docker -v
```
```{bash}
$ docker-compose -v
```
3. Compose the docker container by running 
```{bash}
docker-compose up
```
