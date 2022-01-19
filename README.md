# login_reg

Objectives: 
-Creation of an application that requires registration and login.
  - Check if the email provided is already associated with a user in the database.
  - If YES, then check if the password entered matches the password saved in the database.
-Connection of a Flask application and a MySQL database.
-Understanding the logic required to validate a user logging in to a website.
-The processes associated with a user logging out of an application.
-Session practice!!

RE: Session - Session is how we will keep track of users once they're logged in. In this application, a session variable is used to store the user's id. Using the ID, we're able to gather the rest of the associated user information in the db. Here, we store a single session variable containing the user's id in order to access all of the other information associated with that user.
