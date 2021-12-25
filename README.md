## ORM WEBSITE

The following is a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. this site is completely builted from scratch and deployed it to Heroku. The MVC paradigm in its architectural structure, uses Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.


## User Walk Through

When user visits the site for the first tim then user is presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in.

When the user click on the homepage option the user taken to the homepage. When the user click on any other links in the navigation, then user is prompted to either sign up or sign in. When user user chooses to sign up, then user is prompted to create a username and password

When user clicks on the sign-up button, then the user credentials are saved and the user is logged into the site. When that revisit the site at a later time and choose to sign in, then the user is prompted to enter my username and password.

When the user is signed in to the site, then they see navigation links for the homepage, the dashboard, and the option to log out.

When the user clicks on the homepage option in the navigation, then the user is taken to the homepage and presented with existing blog posts that include the post title and the date created. Wnen I clicks on an existing blog post, then the user is presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment.

When the user enter a comment and clicks on the submit button while signed in, then the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created. When the user clicks on the dashboard option in the navigation, then the user is taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

When the user clicks on the button to add a new blog post, then the user is prompted to enter both a title and contents for my blog post. When the user clicks on the button to create a new blog post, then the title and contents of my post are saved and the user is taken back to an updated dashboard with my new blog post. When the user clicks on one of my existing posts in the dashboard, then the user is able to delete or update my post and taken back to an updated dashboard. When the user clicks on the logout option in the navigation, then the user is signed out of the site. When the user is idle on the site for more than a set time, then the user is able to view comments but the user is prompted to log in again before the user can add, update, or delete comments


## Mock-Up

The following animation demonstrates the application functionality:

![Animation cycles through signing into the app, clicking on buttons, and updating blog posts.](./Assets/14-mvc-homework-demo-01.gif) 

## Getting Started

Your application’s folder structure must follow the Model-View-Controller paradigm. You’ll need to use the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views, use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database for your Models, and create an Express.js API for your Controllers.

You’ll also need the [dotenv package](https://www.npmjs.com/package/dotenv) to use environment variables, the [bcrypt package](https://www.npmjs.com/package/bcrypt) to hash passwords, and the [express-session](https://www.npmjs.com/package/express-session) and [connect-session-sequelize](https://www.npmjs.com/package/connect-session-sequelize) packages to add authentication.

**Note**: The [express-session](https://www.npmjs.com/package/express-session) package stores the session data on the client in a cookie. When you are idle on the site for more than a set time, the cookie will expire and you will be required to log in again to start a new session. This is the default behavior and you do not have to do anything to your application other than implement the npm package.

## Specifications

### Technical
* Upholds to all of the standards plus the following:
    * Application’s folder structure follows the Model-View-Controller paradigm.
    * Uses the [express-handlebars](https://www.npmjs.com/package/express-handlebars) package to implement Handlebars.js for your Views.
    * Application must be deployed to Heroku.

### Deployment: 
* Application deployed at live URL.
* Application loads with no errors.
* Application GitHub URL submitted.
* GitHub repository contains application code.

### Application Quality:
* User experience is intuitive and easy to navigate.
* User interface style is clean and polished.
* Application resembles the mock-up functionality provided in the homework instructions.

### Repository Quality: 
* Repository has a unique name.
* Repository follows best practices for file structure and naming conventions.
* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
* Repository contains multiple descriptive commit messages.
* Repository contains quality readme file with description, screenshot, and link to deployed application.

## Review
Both of these have been sumbitted
* The URL of the functional, deployed application.
* The URL of the GitHub repository, with a unique name and a readme describing the project.

## Built With

* [Express](https://expressjs.com/)
* [nodeJS](https://nodejs.org/en/)
* [mySQL](https://www.mysql.com/)
* [sequelize](https://sequelize.org/)


## Authors
Todd Trulock, PhD,
- [Link to Github](https://github.com/ttrulock1)
- Email:toddstrulock@gmail.com