## HTTP Messages To The Database Server

### General information

First, we created a handler function for the GET request that will be received and added makeDatabaseRequest() function to communicate with a database that will return some data back to the server. Now that we have simple handler functions, we can invoke it when GET request is received. Next, we passed the req and res variables from the .createServer() callback into the handler functions as the first and second arguments, respectively.

### Tools used

+ JavaScript
+ VS
+ node.js
+ command line
