[![Build Status](https://travis-ci.org/victoraldecoa/docker-react.svg?branch=master)](https://travis-ci.org/victoraldecoa/docker-react)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Development

### Run tests and run the service with docker compose

`docker-compose up` runs the tests and makes the service accessible at http://localhost:3000 (or http://192.168.99.100:3000 on Windows with Docker Toolbox)

### Test the production build

`docker build .`

`docker run -p 80:80 IMAGE_ID`

## Available Scripts to run locally

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).