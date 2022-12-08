#  Text Editor (PWA)

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg "MIT badge")

  ## Description

In this project I started with a starter code pack with a fully functioning Google Books API search engine built with a RESTful API, and refactored it to be a GraphQL API built with Apollo Server. The application was built using the MERN stack with a React front end, MongoDB database, Node.js, Express.js and API and was already set up to allow the users to save book searches to the back end.

In this app you can search for books and then save them.

To complete the app I:
    Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.
    Modified the existing authenication middleware so that it works in the context of a GraphQL API.
    Created an Apollo Provider so that requests can communicate with an Apollo Server.
    Deployed the application to Heroku with a MongoDB database using MongoDB Atlas.

The URL of the GitHub repository is:
https://github.com/malvinaH/book_search_engine_MERN ,
and the deployed link is :
https://pure-ridge-40356.herokuapp.com/

  ## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribute](#contribute)
- [Tests](#tests)
- [Questions](#questions)

## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command npm install into the root directory of the terminal. This will install all dependencies in the package.json required to run this application. Don't forget to add .gitignore files to include node_modules before installing npm.

 ## Usage

Run the following commands in the command-line in the root of the folder

    npm install
    npm run build
    npm run develop
    The browser will open at http://localhost:3001/
    Sign Up for an account by entering an email, username, and password
    After signing up, you will automatically be logged in
    Once logged in, you may search for a book
    You have the ability to save books, which you can retrieve at the "See Your Books" tab
    You can search for books again using the "Search For Books" tab
    You may logout by hitting the "logout" button


## License

This application uses the MIT.

  ## Contribute

If you would liek to contribure please for the repo or clone it on your local machine and make a pull request with the suggestions.

  ## Tests

N/A

  ## Questions

If you have any questions about the repo, open an issue or contact directly at hasamalvina24@gmail.com. You can find more of my work at https://github.com/malvinaH.
