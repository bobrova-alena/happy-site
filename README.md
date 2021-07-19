## happy-site
A template for a website.

## Features
- Server side rendering
- Webpack 5+
- TypeScript for both frontend and backend
- React 17+
- Styled System
- Redux-Saga
- Eslint
- Stylelint
- Prettier
- Express
- MongoDB

## Quick start

1.  Make sure that you have Node.js v8.15.1 and npm v5 or above installed.
2.  Clone this repo using `git clone --depth=1 https://github.com/bobrova-alena/happy-site.git <YOUR_PROJECT_NAME>`
3.  Move to the appropriate directory: `cd <YOUR_PROJECT_NAME>`.<br />
4.  Run `npm i` in order to install dependencies.<br />
5.  Add .env file with credentials for you MongoDB.  

`db_name=<YOUR_CLUSTER_NAME>
db_collection=<YOUR_DB_COLLECTION_NAME>
password=<YOUR_PASSWORD>
user=<YOUR_USER_NAME>
cluster_uri=boilerplatecluster.urfud.mongodb.net/<db_name>
uri=mongodb+srv://<user>:<password>@<cluster_uri>?retryWrites=true&w=majority`

7. Run `npm run start` to see the example app at `http://localhost:3080`.

## Documentation
- Styled System: https://styled-system.com
- Redux-Saga: https://redux-saga.js.org/
- MongoDB: https://docs.mongodb.com/manual/tutorial/getting-started/
- MongoDB Atlas: https://docs.atlas.mongodb.com/getting-started/
