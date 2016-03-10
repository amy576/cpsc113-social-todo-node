# CPSC113 Social todo app

This is my app. Hi Kyle and David I am so sorry this is so late.

I tried my best to make everything match the selectors the tests were looking for, but the tests still didn't seem to recognize the selectors. (That being said, I also ran the tests against the example app, which failed 26 tests compared with the 13 failed tests that showed up for my app.

I have, however, manually tested my app against the requirements, and everything seems to work (barring something breaking during deployment to Heroku).

## How to run this
First, run

    mongod

Then, run the server. You can run the server with

    node index.js

or, if you prefer and would like reloading automatically:

    nodemon index.js
    
To run the server with the MongoDB URL and the session ID, enter the following:

    MONGO_URL='mongodb://localhost:27017/social-todo' SESSION_SECRET='foo123' nodemon ./index.js

Lastly, run

    mongo

to start the MongoDB shell and connect to the database.
