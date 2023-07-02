This is a modified version of the public MMO Games API. Used for MMO Games app https://github.com/Renardo1985/phase-2-project. coded by Renardo Williams.

The API was used to populate the games section with all currently LIVE games.Also, you can favorite games you like and view them later, search for MMO Games by title from the games section. Finally, you can learn the details about your favorites by selecting see more.


## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Resetting Data


Then, run `npm run seed` to copy data from the `db/seeds.json` file to the
`db/db.json` file. `json-server` uses the `db.json` file to create your RESTful
API, so make sure your `db.json` file is always up to date!


## Running the Server Locally

To run your server in development mode, run:

```sh
npm start
```

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3001](http://localhost:3001). Check it out in the browser to
make sure your server works!


## Acknowledgments and Credits

https://www.mmobomb.com/api
https://github.com/learn-co-curriculum/json-server-template/tree/main