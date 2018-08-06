Years To Read
===============

[years-to-read.com](http://years-to-read.com) is a web app that tells you how long it will take you to read a book. It's build on top of Vue and Express and uses the Google Books API.

![Years To Read](https://i.imgur.com/zW3s8x7.png)

### Requirements
* Node >= 9
* Google Books [API-Key](https://developers.google.com/books/).

### Installation
* Clone this repo
* Copy `.env.example` to `.env` and enter you `GOOGLE_API_KEY` 

### Development
* Run `npm install`
* Run `npm run build`
* Start the Express server in a new tab via `node src/express.js`
* Server will be running on `http://localhost:3000`

### Production Build
* Run `npm run prod`
