# REACT CRUD EXAMPLE - modern version

## Introduction

This a basic crud react-hooks-context-feathers application for managing contacts. It currently uses MongoDB for the database and Feathers for the REST API server.

See tutorial: https://www.sitepoint.com/crud-app-react-redux-feathersjs/

This is an updated version of the older project that is now in legacy mode: https://github.com/brandiqa/redux-crud-app.

##  How to install

The following instructions assume you have installed Yarn.

```bash
git clone git@github.com:brandiqa/react-crud-example.git
cd react-crud-example

# Install frontend dependencies
yarn install

# Install backend dependencies
cd backend
yarn install
```

## How to run
Ensure you have mongodb installed in your system and that it is running.

### Start Feathers backend server
Start the backend server first:

```bash
cd react-crud-example/backend
yarn start
```

This will launch the backend server at localhost:3030. If all is working well, you should be able to access the url http://localhost:3030/contacts from your Browser, Postman or Insomnia.

### Start `create-react-app` server
Open a separate terminal to start the client:

```bash
cd react-crud-example
yarn start
```

Your default web browser will be launched automatically with the url http://localhost:3000

## License

The MIT License (MIT)

Copyright (c) 2020 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

"# react-using-form" 
