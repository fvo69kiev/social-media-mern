# Social-media-mern

## Introduction
Social-media-mern is a Full Stack MERN Application.
You can build the App using React, Node.js, Express & MongoDB.
It is a simple social media app that allows users to post interesting events that happened in their lives.

## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then server and add the following

```
PORT = 5000
CONNECTION_URL = your mongodb uri
SECRET = 'test'
```
Replace in client->src->components->Auth->Auth.js
```
clientId = your Google client id
```
##Setup:
- run ```npm i && npm start``` for both client and server side to start the app