# week14-reverse-engineering-code
Unit 14 Sequelize 

# Files Explained 
 - isAuthenticated.js Authenitcation method restricts routes that user is not allwed to visit of not logged in. If the user is Authenticated the request continues. 
 - config.json contains the configuration to connect to the server.
 - passport.js contains the javascript logic that tells passport that a user is logging in with email address and password. 
 - index.js connects to the database and imports users login data.
 - user.js this js files defines what is stored in the application database.
 - api-routes.js this file contains routes for signing in, logging out, and getting user specific data to be displayed in the user browser.
 - html-routes.js checks to see if the user is Authenticated and has an accout and sends them to the requested html page.
 - package.json this file holds various metadata relevant to the project i.e. contains all package information, node modules installed and version information. 
 - server.js containes the configuration information for the node server supporting the application 

# Install Application
 - In SQL workbench create a db called "passport_demo"
 - Configure the config.js file to match your SQL environment. 
 - run npm i
 - execute node server.js
 - open local browser with http://localhost:8080 