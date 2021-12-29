# Simple SNS

A simple SNS service with Kakao API sign in, simple sign in, posting, searching hash tag, following function.
Used Node.js, MySQL(with sequalize), express, passport, sequalize.

/models: MySQL codes
/routes: express.Router codes
/view: html codes with nunjucks
/passport: sign in implementation with passport module

run commands <br>
$ npm install <br>
$ npm run build:parser    // Convert /src/index.js to /public/bundle.js with webpack module <br>
$ npm start <br>

![nodebird](./screenshots/login.png)
![nodebird](./screenshots/timeline.png)
