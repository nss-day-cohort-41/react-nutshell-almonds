# Team Almond's Group Project: Nutshell 2

Team Almond was tasked with creating a social media app with CRUD functionality utilizing React.js using the criteria listed below.

Concepts covered in this project include: session storage, creating a JSON database, CRUD functionality with API fetch calls to JSON server, associating that data with a userID, JavaScript, HTML, CSS, React.js.

PICTURE GOES HERE

## Erik Lindstrom
- Created registration page and process
- Modified login page to require accurate username and password
- Created articles section
- Fetched article data from database to display on DOM
- Created new form with the ability to post new data to database from DOM
- Created delete button with the ability to delete events object in database from DOM
- Added functionality to only allow articles belonging to logged in user to be deleted


## Christopher McColgan
- Created tasks section
- Created events section
- Created README file
- Tasks and events sections only show data belonging to the logged in user
- Tasks and events sections have full CRUD functionality

## Jon Riley
- Created friends section
- Created new form with the ability to post new data to database from DOM
- Created edit form with the ability to edit data in database from DOM
- Created delete button with the ability to delete events object in database from DOM

## Trigg Summs
- Created messages section
- Created navbar
- Created new form with the ability to post new data to database from DOM
- Created edit form with the ability to edit data in database from DOM
- Created delete button with the ability to delete events object in database from DOM

## Setup
1. Clone this repository
1. `cd` into the directory it creates
1. `npm install` to install react.js
1. Make a `database.json` file in the `api` directory, or use existing `sample.json`
1. `cd` into `api` directory and enter `json-server -p 5002 -w database.json` to serve json file
1. `cd` into main directory and `npm start` to make app acessable via web browser

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

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

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
