# ReSprint

## Server Requirements

For development, you will only need Node.js

## Node

- ### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
  Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- ### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- ### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

## Structure

The main directories are:

| Directories    | Description                                                                                                                      |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| `server/config`      | This directory contains database configuration file                                                                              |
| `server/data`        | This directory contains all the business logic of the application and database operations with respect to different endpoints    |
| `server/middlewares` | This directory contains all the middleware logic for the application for eg authentication                                       |
| `server/models`      | This directory contains all the sequelize definitions of the tables in the databse                                               |
| `server/routes`      | This directory contains all the routes for the application                                                                       |

The entry point of the application is located in `index.js` from where the express server starts

## Configure app

### You will need to first install all the dependencies by running this command

    $ npm ci

### Then you will need an .env file to make sure all the configurations are in place to run the application

### Start the application using command

    $ npm start
