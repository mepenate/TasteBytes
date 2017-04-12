# Todo app with Angular2, AngularFire2, and Firebase SDK 3
A simple Point-of-sale application and website built with **ExpressJS** and **NodeJS**. The app features a **Firebase** backend and authentication. Try the demo at <a href="https://tastebytes-e421e.appspot.com" target="_blank">tastebytes-e421e.appspot.com</a>.

- ExpressJS `4.15.2`
- Firebase SDK `3.7.5`
  - JSON Datastore
  - Simple email/password OAuth authentication. Support for Google/Twitter/Github possible later
- Google App Engine Hosting
- Semantic UI with SASS
- Handlebars


Quick Start
-----------

Ensure you have the latest version of node and npm installed. You can install these @ https://nodejs.org/en/

```shell
$ git clone https://gitlab.com/tasteBytes/dashboard
$ cd dashboard
$ npm install
$ npm run
```
The server will now be open at localhost:3000 and will restart with any changes to the project.

## Deploying to Google App Engine
#### Prerequisites:
- Make sure that you have privilege to deploy
- Install the Google Cloud SDK <a href="https://cloud.google.com/sdk/" target="_blank">Grab it here</a>
- Ensure that you are in the root directory of the project.
- Run the command 'npm deploy'

Commands
--------

|Script|Description|
|---|---|
|`npm start`|Necessary command to deploy to google app engine.|
|`npm run`|, Start the express server @ `localhost:3000`; watches for changes to re-run the server on change.|
|`npm deploy`|Starts the deployment process to google app engine|
|`npm test`|Run unit tests with Karma and Jasmine|
