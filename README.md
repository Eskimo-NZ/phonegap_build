#Client-Side Example PhoneGap Build

This repository was made as a fully working PhoneGap build that incorporates all of the necessary calls to our server that is needed to make the final PhoneGap build.

The code in this repository was solely compliled by *Alex Candler*

###Files

**www/**

  **index.html** - Verify user call (Passes up a userID, recieves json with all of that user's infromation and puts it in localstorage for later use), links to the Facebook authorisation page (opens the page using an "inAppBrowser" which is a PhoneGap addon).

  **staff.html** - Gets and displays all of the users from the server, Update call for changing the Green Man points (enter the userID and the new amount of points)

  **greeenman.html** - Gets the latest version of the user's data (uses the user's id that is in localstorage)

  **events.html** - Gets all the events from the server and displays it, Create an event and post it to the server (contains title, description, lat, long and points value)

  **newsfeed.html** - Gets the latest news from the server and displays it, Posts a comment to the server (uses the fullname of the user in localstorage to send with the news/comment)
