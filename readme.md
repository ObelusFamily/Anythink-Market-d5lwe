# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

After installing docker on your machine,
Please run docker compose up and wait for all services to come up.
Now, go to  ([http://localhost:3000/api/ping](http://localhost:3000/api/ping) on your browser and make sure you get the response:
`{"msg":"Pong! Seems like Everythink is working, great job!"}`
Then, go to ([http://localhost:3001/register](http://localhost:3001/register) and `create a new user`.
You're all set!