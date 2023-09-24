# Book Search Engine Starter Code

## Description

This project's goal was to refactor a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API.

The following was executed:

1. Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

2. Modify the existing authentication middleware so that it works in the context of a GraphQL API.

3. Create an Apollo Provider so that requests can communicate with an Apollo Server.

4. Deploy the application to Heroku

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

If running on local:

1. execute npm i
2. npm run develop

## Usage

Deployed: [https://booksearchengine33-ae8ccc777508.herokuapp.com/](https://booksearchengine33-ae8ccc777508.herokuapp.com/)

A user first must make an account and sign in. Once that is done they will be able to search for books through Google Books API search engine and add that to a reading list. The user can then access the reading list to revist their saved books. They can also remove books from their list as needed. 

## Credits

forked from starting code @ [https://github.com/coding-boot-camp/miniature-eureka](https://github.com/coding-boot-camp/solid-broccoli)

## License

Refer to license inside the repo. 

## Badges

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)(https://opensource.org/licenses/MIT)
