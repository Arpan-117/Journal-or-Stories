# Journal-or-Stories
For users to add/delete stories or journal entries like a personal diary

This a project made using NodeJS, Express and EJS Template. Data is stored using a local MongoDB Database. This is a web app for a user to make diary or journal entries with a title and some content. The homepage will have a single line of all the entries of the user displayed. On clicking 'read more', user will be redirected to the full journal entry page. The 'Compose' button on the homepage will allow users to add new entries. It will redirect users to the compose page wher the user has to enter the title and content of their entry. Once that is done the 'Post' button will sumbit the entry and redirect to the hompage which will now include the new journal/diary entry.

HOW TO RUN
-download and install NodeJS and MongoDB
-download and install the dependencies from the package.json file
-set up and configure the MongoDB server in your local machine
-spin up the MongoDB server (mongod)
-start up the mongo shell (mongo or mongosh [depends on how it is configured])
-start the app using node commands (node app.js or nodemon app.js)
