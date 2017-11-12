# bapi-p3-the-scoop

This is the 3rd project in build Apis from scratch in codeacademy.
In this project, you will build all of the routing and database logic for an article submission web app called The Scoop.

The Scoop allows users to:

Create and log in to custom username handles
Submit, edit, and delete articles containing a link and description
Upvote and downvote articles
Create, edit, and delete comments on articles
Upvote and downvote comments
View all of a user's articles and comments

Our job was to add the routes and database handling for comments and add persistent database using yaml (bonus).

I did not upload the node_modules directory as it was too big, however I installed the yaml modules using -D tag and they are in package.json so I assume that npm install will install all necessary modules.

I originally created const status codes to make my code more readable, however as the original code used hardcoded integers and I did not wish to chnage the original code I didn't use them in the end to make the code more consistent. I kept the constants so I could verify my codes but they were not used.
