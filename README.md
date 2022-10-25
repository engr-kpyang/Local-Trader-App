
# Local Traders Solo Application

## Description

Local traders is a marketplace application that helps users buy and sell local collectibles. This application help user easily connect with sellers by displaying their contact information. Users are able to view the marketplace without loggin but cannot take any further action without logging in. 

Project duration: 2 weeks

## Prerequisites/Installation

Before you get started, make sure you have the following software installed on your computer:

- [Node.js](https://nodejs.org/en/)
- [PostrgeSQL](https://www.postgresql.org/)
- [Nodemon](https://nodemon.io/)

Run:
- npm Install

## Create database and table

use the database.sql file here to upload the queries to your database. Run the queries to create all the required tables and data.

## Development Setup Instructions

- Run `npm install`
- Create a `.env` file at the root of the project and paste this line into the file:
  ```
  SERVER_SESSION_SECRET=superDuperSecret
  ```
  While you're in your new `.env` file, take the time to replace `superDuperSecret` with some long random string like `3645g4ae6r54ge65f4gae6r4` to keep your application secure. Here's a site that can help you: [https://passwordsgenerator.net/](https://passwordsgenerator.net/). If you don't do this step, create a secret with less than eight characters, or leave it as `superDuperSecret`, you will get a warning.
- Start postgres if not running already by using `brew services start postgresql`
- Open a terminal and run `npm run server`
- Open a new terminal and Run `npm run client`
- Navigate to `localhost:3000`

## Support
If you need assistance, feel free to email me at kpyang2414@gmail.com
