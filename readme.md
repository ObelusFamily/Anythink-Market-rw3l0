# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Open terminal and check installations are OK by runnig:
   docker -v
   docker-compose -v
2. Clone the repo
3. Go the the local repo path
4. Run: docker-compose -v
5. To verify backend was installed successfully go to: http://localhost:3000/api/ping
6. Tp verify frontend was installed successfully go to: http://localhost:3001/register and register
