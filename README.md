# Less waste more taste

An app to find fun cocktails with what you have at home!
This is a JavaScript project utilising React for the user interface.

Created by [Thomas Mannion](https://github.com/TomMannion), [Marina Ivanova](https://github.com/MarinaIvanova-1), [Yichao](https://github.com/oahciy), [Jean Bustinza](https://github.com/jeanbu) and [Sadat Manjur](https://github.com/Sadat15).

It uses:

- [Express](https://expressjs.com/) web framework for Node.js.
- [React](https://reactjs.org/) to render view templates.
- [Bootstrap](https://getbootstrap.com/) for styling.
- [Mongoose](https://mongoosejs.com) to model objects in MongoDB.
- [ESLint](https://eslint.org) for linting.
- [Jest](https://jestjs.io/) for unit and intergration testing.
- [Cypress](https://www.cypress.io/) for end-to-end testing.

## Hosted on Heroku

[Waste less taste more!](https://less-waste-more-taste.herokuapp.com/)

## If you want to try this on your computer, download this repo and follow these instructions:

### Install Node.js

1. Install Node Version Manager (NVM)
   ```
   brew install nvm
   ```
   Then follow the instructions to update your `~/.bash_profile`.
2. Open a new terminal
3. Install the latest version of [Node.js](https://nodejs.org/en/), currently `18.1.0`.
   ```
   nvm install 18
   ```

### Set up your project

1. Fork this repository
2. Clone your fork to your local machine
3. Install Node.js dependencies in both the server and client folders.
   ```
   cd server
   npm install
   cd ..
   cd client
   npm install
   ```
4. Install MongoDB
   ```
   brew tap mongodb/brew
   brew install mongodb-community@5.0
   ```
   *Note:* If you see a message that says `If you need to have mongodb-community@5.0 first in your PATH, run:`, follow the instruction. Restart your terminal after this.
6. Start MongoDB
   ```
   brew services start mongodb-community@5.0
   ```

### Start

1. Start the server
   ```
   cd server
   npm start
   ```
2. Start the client in a new terminal
   ```
   cd client
   npm start
   ```
3. Browse to [http://localhost:3000](http://localhost:3000)
