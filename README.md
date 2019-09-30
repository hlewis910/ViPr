#

Create application forms and track them.

### Tech Used
- Express
- PostgreSQL
- React.js
- Sequelize

### Install
Clone the repo and install npm packages
```bash
git clone https://github.com/inclusion-red/Red-Tracker.git
cd Red-Tracker
npm install
```
This should install root packages, /client packages, and /server packages

### Start Development
To start dev start npm inside the project folder
```bash
npm run start-dev
```
This should run react server for frontend and nodemon for express server (server).


### Regular start
To start the project then you need to build the frontend (cause of react) then start the server
```bash
npm run build-client
npm start
```
This should run without nodemon or react server.
