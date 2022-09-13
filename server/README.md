Debug
If your 'nodemon server.js' didn't work make sure the following things are done:

Make sure your MongoDB server is running (the 'mongod' command)
Make sure your post data matches the data that you are inserting into the database (name and age)
Make sure that your form submits a post request to '/users'
Make sure mongoose is actually installed
Check the order of everything related to mongoose (require --> connect --> Schema --> Model --> route)
Use lots of console.log statements and follow the flow of data.