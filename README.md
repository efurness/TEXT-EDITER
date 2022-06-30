# TEXT-EDITER

[GitHub license](https://img.shields.io/badge/license-undefined-blue.svg)

# DESCRIPTION 

This is a single-page application using an `IndexedDB API` with ability to run live or offline in an internet browser.  It offers the ability to be installed as a Progressive Web Application.  Users can create notes or code snippets when they're are traveling or in the field because of data persistence.  A `manifest.json` file is made using the `WebpackPwaManifest` plug-in.  Additionally, a `service worker` is created using `workbox` that caches static assets.  The application is deployed to Heroku.

# TABLE OF CONTENTS 

  - [Project Description](#project-description)
  - [Deployed To ](#deployed-to)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Tests](#tests)
  - [Questions](#questions)
  - [Contact](#contact-me)


## DEPLOYED TO

[TECH BLOG Site - GitHub] (https://github.com/efurness/TEXT-EDITER.git)

[TECH BLOG Site - HEROKU] (https://shrouded-plateau-24724.herokuapp.com/)

# INSTALLATION 

`NODE JS, Express.JS, NPM install to retrieve the packages, node modules`.  IndexedDB API to include GET, PUT methods using NPM IDB light-weight wrapper. WebPack to bundle application.  "express": "^4.17.1", "if-env": "^1.0.4".  The application uses `babel` in order to use `async / await`.  `Concurrently": "^5.2.0", and "nodemon": "^2.0.4"`

[express 4.18.1](https://expressjs.com/)

[To install the Heroku CLI](https://coding-boot-camp.github.io/full-stack/heroku/how-to-install-the-heroku-cli)

[Heroku documentation on creating a Heroku remote](https://devcenter.heroku.com/articles/git#creating-a-heroku-remote)

[Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).


## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

# USAGE 

General usage for building an TEXT EDITOR APPLICATION.


 
# LICENSE 

Open source license

# CONTRIBUTING 

Solo Project, Contributors welcome

# TESTS 

Tests were run to establish routes
 
# QUESTIONS 

 * For additional help or questions, please reach out to Ellen.Furness@du.edu.



## CONTACT ME



* Follow me on Github at [efurness](http://github.com/efurness)


