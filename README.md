This a to-do list app created to add and keep track of multiple tasks throughout the week.
This app was built using MonngoDb, Express, NodeJS and React (MERN stack).

To connect the app to backend download the code and start the server using "node server.js".
This repository aims to assist you in beginning work on a MERN stack application with a solid file structure as a foundation. To get started make a copy of this template repo for your project teams.

Since this project will hold both the client application and the server application there will be node modules in two different places. First run npm install from the root. After this you will run npm run-script install-all from the root. From now on run this command anytime you want to install all modules again. This is a script we have defined in package.json .

This app can be deployed directly to heroku since there is a script defined in package.json which will automatically handle building and deploying the app. For more information on deploying to heroku reference the extra resources at the bottom of this file.
npm run-script dev
Runs both the client app and the server app in development mode.
Open http://localhost:3000 to view the client in the browser.

npm run-script client
Runs just the client app in development mode.
Open http://localhost:3000 to view the client in the browser.

npm run-script server
Runs just the server in development mode.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

If deploying to heroku this does not need to be run since it is handled by the heroku-postbuild script

See the section about deployment for more information.

Learn More
You can learn more in the Create React App documentation.

To learn how to setup a local MongoDB instance for testing, check out how to Connect to MongoDB.

To learn how to deploy a full-stack web app to heroku, check out this great guide.

To learn React, check out the React documentation.

npm run build fails to minify

