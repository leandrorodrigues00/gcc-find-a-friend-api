# Green Chain Challenge! - Find a friend - API 🐶

This is the API of the FindAFriend project, which aims to connect people interested in adopting pets to organizations that make pets available for adoption. The API is responsible for providing the necessary data for the web application to work correctly.

To use the application, you need to run both the server and the web application. Follow the instructions below to set up the API, then download and run the web application available in the repository at: [Find A Friend Web](https://github.com/leandrorodrigues00/gcc-find-a-friend-web).

The web application repository provides a detailed description of the project as well as the technologies used and a demonstration of how it works. Take the opportunity to explore it and better understand how the FindAFriend API operates!

## 💻 Getting started

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [NPM](https://www.npmjs.com/) _(examples are with NPM)_

### Installation

**Clone the project and access the folder**

```bash
$ git clone https://github.com/leandrorodrigues00/gcc-find-a-friend-api && cd gcc-find-a-friend-api

```

**To run the back-end application, you need to follow the steps below**

```bash
# Install the dependencies
$ npm i

# Make a copy of '.env.example' to '.env'
# and set THE SAME environment variables.

$ cp .env.example .env

# Run the database migrations with the command
$ npx prisma migrate dev


# Run seeds to populate the database with test data with the command
$ npx prisma db seed


# Start the app
$ npm run dev
```

**Your API will be available at the URL http://localhost:3333**
