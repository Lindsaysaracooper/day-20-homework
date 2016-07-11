## Day 21- Build Tools, NPM, ES6, Underscore

### Challenge
- write a function called forEach that takes an array and a callback as it's two arguments. Works like .forEach but doesn't use it
- answer on codepen

### Modular code
- Building pieces of code and pulling them into your project. Less code in project. Cleaner way to present code.
- Build Tools
  - Gulp, Grunt, Broccoli, Webpack
  - NPM - Node Package Manager

- npm install --save jquery this adds into the devDependecies in the packakage.json. Any time you want to add a library, change -> npm Install--save whatever
- ** SPA Scafold www. github.com/tiy-austin-front-end-engineering/spa-scaffold

**- Only work in the app files- dist is for live files and not for editing.**

## STEPS
- For each new project:
- Clone this repo (or fork then clone, if you prefer)
`https://github.com/TIY-Austin-Front-End-Engineering/spa-scaffold`
  - git clone "the link from the new repo you create on github" then the folder you want it to go. Example the below is creating an examples folder inside day-21:
  `tiy git clone https://github.com/TIY-Austin-Front-End-Engineering/spa-scaffold.git day-21/examples`
- Remove the git history by running rm -rf .git
- Steps like normal
  - Add git init
  - Set up a new git repo
- Run npm install
 - To add jquery
  - run npm Install--save jQuery
  - inside the entry.js
    - import $ from 'jquery'; - this is the syntax to use modules in js. this is like a variables declaration similar to scss
    - $('#container').append('i added this with jQuery')
- **Also need to add a configuration file to your project called .jshintrc**    
- so inside the folder (in this case 'example') add .jshintrc
and inside that folder:
    - {"esversion":6}

### Babel pronounced ('bay-ble') and Import and export variables
- a way to make sure js is up to date. Turns regular js into es2015 code.
- Anytime you want to use var from other files:
  - export default whatever;
  - import whatever from './nameofjsfile' on the main entry.js page 
