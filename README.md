# Kitabghar SPA (Angular 6)

### Description

Kitabghar is a simple single page application (SPA) that lets you buy all the books that are available in the store. You can also see all of your purchased books history.
Find books based on Title, genre, publisher, ISBN.

### Tech

It uses number of open source projects to work:
* [MongoDB](https://www.mongodb.com) - Free and open-source cross-platform document-oriented database
* [Mongoose](http://mongoosejs.com/index.html) - Elegant MongoDB object modeling for NodeJS
* [NodeJS](https://nodejs.org/en/) - Evented I/O for the backend
* [ExpressJS](https://expressjs.com) - Fast, unopinionated, minimalist web framework for NodeJS
* [JSONWebToken](https://jwt.io) - Used for authorization
* [Angular](https://angular.io) - Platform that makes it easy to build applications with the web


### Installation

Book Store requires 
* [MongoDB](https://www.mongodb.com/download-center#community) v3.6+
* [NodeJS](https://nodejs.org/en/) v8+

To start the database (port: 27017): Install MongoDB, open new cmd window (in project root) and run

```sh
$ cd server
$ start-mongodb
```

To add initial seeding: (do this step once only the first time you start the app)
After you start MondoDB open new cmd window (in project root) and run

```sh
$ cd server
$ seedBooks
```

To start the server (port: 8000): open new cmd window (in project root) and run

```sh
$ cd server
$ npm install (if you havent already installed the dependencies)
$ npm start
```

To start the client (port: 4200): open new cmd window (in project root) and run

```sh
$ cd client
$ npm install (if you havent already installed the dependencies)
$ ng serve
```

### Features

- Anonymous users
    - Login/Register
    - View all books
    - View books details

- Authenticated users
    - Buy books
    - Rate books
    - View user profiles
    - View his own purchases history

- Admin users
    - Add books to the store
    - Edit books
    - Delete books


### License
MIT
