# ![My image](./README_logo.png) Welcome to the [*SiteKite.co*](http://sitekite.co/) Github Repository! ![My image](./README_logo.png)

[![Coverage Status](https://coveralls.io/repos/github/tommygaessler/sitekite/badge.svg?branch=master)](https://coveralls.io/github/tommygaessler/sitekite?branch=master)

[Here is the Deployed Website](http://sitekite.co/)

## What is SiteKite?
SiteKite is an application developed and designed by 5 Galvanize students for the Unit 2 Project. This website is designed to make creating a personal portfolio website fast, easy, and fun. It will also make it easy for a company to view your portfolio, and if they like what they see, they can contact you directly from your personal portfolio!

### How does it work?
When you log into our website using your github account, SiteKite auto populates an entire portfolio for you. You can then change the theme/layout of your portfolio, add more detailed descriptions, add/edit your projects, and change any information that was pulled from github. This allows you to make the portfolio you create with SiteKite more personalized.

#### Please follow the steps below to get SiteKite set up for local development.

1. git clone or fork this repo
1. Create a .env
  - _hint:_ re-name the `.sample_env` file to `.env` and insert the appropriate data in the "quotes"
1. go into *src/server/config/main-config.js* and uncomment line 22
1. run `npm install` in the terminal.
1. run `createdb site_builder` in the terminal.
1. run `knex migrate:latest` in the terminal.

#### To start the server locally

1. Run `gulp` in the Terminal/Command Line

#### To run SiteKite locally
1. Complete all of the above steps
1. Copy and paste `http://localhost:3000/` into your browser

>### Development Team
- Isaac Collier
  - [view Isaac's github](https://github.com/Isaacjcollier)
- Tommy Gaessler
  - [view Tommy's github](https://github.com/tommygaessler)
- John Berger
  - [view John's github](https://github.com/johnmberger)
- Austin Mahan
  - [view Austin's github](https://github.com/AustinMahan)
- Alex Glassford
  - [view Alex's github](https://github.com/abglassford)
