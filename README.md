# WeatherZen Backend Application

Backend server for Weatherzen application. Weatherzen is an application that crowd sources local weather observations.

## Existing files

| Folder/file path                 | Description                                                                                                           |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| `src/app.js`                     | Directs requests to the appropriate routers.                                                                          |
| `src/server.js`                  | Starts the server on `localhost:5000` by default.                                                                     |
| `src/db/`                        | A folder where you will add migration and seed files for your database later on.                                      |
| `src/errors/`                    | A folder where you will find several functions for handle various errors                                   |
| `.env.sample`                    | A sample environment configuration file                                                                               |


This starter code closely follows the best practices and patterns established in the Robust Server Structure module.


## Installation

1. Fork and clone this repository.
1. Run `cp .env.sample .env`.
1. Update your `.env` file with a connection URL to your Postgres SQL database instance.
1. Run `npm install` to install project dependencies.
1. Run `npm run start:dev` to start your server in development mode.

