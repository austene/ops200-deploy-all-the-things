# ops200-deploy-all-the-things

## Purpose of Program
Confirms that all React100 apps are deployed to Heroku.

## Setup

### Clone
Clone respository
### Install Dependencies
```
$ npm install
```
### Run
1. Open a browser at localhost: 3000

2. Build and start server
```
$ npm start
```
- npm run build and npm start combined in package.json with `npm start`.

3. Testing
```
$ npm test
```
Must run test twice:
- 1st time wakes up the sleeping Heroku apps.
- 2nd time passes the tests.