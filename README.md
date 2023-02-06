# JATE - Just Another Text Editor

## Project Description
JATE is a single-page text editor application that runs in the browser. This application meets PWA criteria and features multiple data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. Additionally, this application is available for installation and is fully functional offline.


---
## Tools Used to Create This Project
* JavaScript ES6
* Node.js
* Express.js
* Concurrently
* Babel
* Webpack
* Workbox
* IndexedDB
* idb
* Heroku

## Usage
The application is deployed on Heroku at https://glacial-lake-65417.herokuapp.com/

Visit the website on Heroku. You can view posts and visit links as a visitor or create your own account. Click the sign in button in the upper right hand corner of the application. If you do not yet have an account, click the link below the form to create an account. Once you've set your credentials, you will be prompted to select an avatar and create an about section. As an authenticated user you can add, delete and edit your own posts and comment on other posts.

Warning: New data is stored on Heroku for an indeterminate period of time. At least once a day the dynos will be restarted and any new data included new users might be wiped out.

