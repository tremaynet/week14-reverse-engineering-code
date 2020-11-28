# week14-reverse-engineering-code
Unit 14 Sequelize 

# Files Explained 
 - isAuthenticated.js Authenitcation method restricts routes that user is not allwed to visit of not logged in. If the user is Authenticated the request continues. 
 - config.json contains the configuration to connect to the server.
3. passport.js contains the javascript logic that tells passport that a user is logging in with email address and password. 
4. index.js connects to the database and imports users login data.
5. user.js this js files defines what is stored in the application database.
6. api-routes.js this file contains routes for signing in, logging out, and getting user specific data to be displayed in the user browser.
7. html-routes.js checks to see if the user is Authenticated and has an accout and sends them to the requested html page.
8. package.json this file holds various metadata relevant to the project i.e. contains all package information, node modules installed and version information. 
9. server.js containes the configuration information for the node server supporting the application 

# Install Application
1. In SQL workbench create a db called "passport_demo"
2. Configure the config.js file to match your SQL environment. 
3. run npm i
4. execute node server.js
5. open local browser with http://localhost:8080 