# TechBlog-Model_View_Controller

## GitHub 
The URL of the GitHub repository
https://github.com/Darigay/TechBlog-Model_View_Controller

## Heroku
Deployed Heroku Link.


## Table of Contents
- Description
- usage
- Technologies
- Dependencies
- Resources
- Contact

## Description:
Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

The Tech Blog Application build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. This deployed application follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Usage
In this CMS-style blog site. When the user visits the site for the first time,then they are presented with the homepage which includes 
existing blog posts if any have been posted earleir by other tech bloggers.
The Nav bar on the main page gives user navigation links for the homepage and the dashboard along with a the option to log in.
On Click of Anything on the DAshboard, the user is prompted with signup or signin option. The User can signup or signin with the links in navigation bar.
User when chooses to sign up, they are prompted to create a username and password and click on the sign-up button.
The user credentials are saved and they are logged into the site, when they revisit the site at a later time and choose to sign in with the credentials provided in login page. 
Upon signing into the site, in the navigaion bar links for the homepage, the dashboard, and the option to log out are provided.When the user clicks on homepage option in the navigation, the user is taken into the homepage and presented with existing blog posts that include the post title and the date created, when clicked on an existing blog post, the user with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment.User can enter a comment and click on the submit button while signed in , upon which the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created.
On click on the dashboard option in the navigation, user is taken to the dashboard and presented with any blog posts user have already created and the option to add a new blog post.On click on the button to add a new blog post, user is prompted to enter both a title and contents for blog post.
The User onclick on one of my existing posts in the dashboard is able to delete or update my post and taken back to an updated dashboard.
Finally, the user onclick on the logout option in the navigation is signed of the site.

## Technologies
- Javascript
- Node.Js
- express.js
- mysql2
- npm packages 
- Github

## Dependencies
- CLI
- MySQL2
- Sequilize
- dotenv package
- bycrypt


## Resources
- UofU BootCamp Object-Relational Mapping (ORM) Modules and MVC module
- Sequilize Documentation

## Contact
Email Address : divya.arigay@gmail.com 
Github: Darigay@github.com


© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.