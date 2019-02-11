# Bullhorn

Only have one user and one Admin. More users will greatly complicate the application at this point. Don't go there!!

You are to write an application that is kind of like twitter. It will allow a user to
post a message, and everyone else to see all the messages that have been posted. It will also feature a user profile which displays a user's name, email and motto. 

The logged in User should display on every page (except login).

There should be a link to logout which, when clicked, logs out the user and redirects them to the login page

Users can edit and delete their own messages and their profile. 

Build an application that allows you to add MESSAGEs, list them and view them (like Lesson 10)

### Message object should have at least:
- long id
- String content
- Date posteddate
- String sentby

### Features/Functionalities:

- The home page ("/") path should point to a list of all MESSAGE's
- Every page (or template) should have link (or button) to the add path 
("/add") which is the new MESSAGE form
- Implement Bootstrap to make it look good
- Use a MySQL to store your messages (Don't forget the MySQL and JPA dependencies)
- Definitely use page fragments (refer to Lesson 16). These are really useful for the navbar.
- Make sure you are able to at least update and show the message in another page (show and update)
