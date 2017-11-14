# Angular Contacts 1: Project Setup

## Setup

* Create a branch named ```part1```.  ALL of your work for this assignment needs to be completed on that branch.  
* DO NOT merge the part1 branch into master UNTIL you have a thumbs up from an instructor.

## Requirements

1.  Project Setup
* Set up a new project as you always have, with this general structure:
  ```
  |- javascripts/
  |  - controllers/
  |  - services/
  |  - AppConfig.js
  |  - AppConstants.js
  |  - AppConstants.js.example
  |  - app.js
  |- lib/
  |  - Gruntfile.js
  |- sass/
  |  - main.scss
  |- styles/
  | .gitignore
  | index.html
  | README.md
  ```
* Technologies:
  * Angular
  * Bootstrap
  * Jquery
  * Font awesome
  * Sass

* Make sure that your .gitignore includes:
  * .DS_Store
  * javascripts/AppConstants.js
  * lib/node_modules
  * public


2. Routes

Set up each of these routes, each with a corresponding partial and controller. When I go to each route initailly, I should see "Hello, [Route Name]" in both the HTML and the console (hard-coded, just to make sure the route is fully working).
 > * login
 > * contacts/view
 > * contacts/new
 > * contacts/favorites

3. Deploy

The app should be able to deploy to Firebase with no errors in the console. Put the link to your hosted project in your README as soon as you get it hosted. You don't have to have the full README yet, but get that link in there!
