# HeadLess React App with WP-REST-API
Simple single page app using react to pull in content via WordPress API

# Why?

I wanted to learn React with my existing knowledge of WordPress. What better way then to build a single page app with the improved WP-REST-API!

# Currently

The app pulls in posts, categories, and has a simple login feature in which you can delete a post.

# Installation

To run the project on localhost:8080:

`npm start`

Project uses [JWT for Authentication](https://wordpress.org/plugins/jwt-authentication-for-wp-rest-api/). You will need to install the plugin and configure accordingly if you wish to use the login feature.

Make sure to update the ***src/auth.js*** with the apporiate URLs. 


# To-Dos
- add error handling for failed logins
- add search to the page
