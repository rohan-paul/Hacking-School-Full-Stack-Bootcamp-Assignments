This small code will server the static theme templated-hielo (a frrely available template) template from the root route of my express server after starting the server.

**index.js file** - This file will show me the html theme directly as soon as I open the home page by starting up the server with ``$ node index.js``

**server.js file** - This file will show me the list of directories and files as soon as I start up the server with ``$ node server.js``

**server-express.js file** - Implementing the same functionality as **server.js**, only here, I am using Express to set the base path with ``app.use``. Running the server will show show me the list of directories and files as soon as I start up the server with ``$ node server.js``