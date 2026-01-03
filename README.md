# Real Time Chat App
- A real-time chat application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) using Socket.IO for live messaging and JWT authentication for secure login/signup.
- This project provides a full-stack solution with real-time messaging, online user presence, and a modern React UI styled using TailwindCSS + DaisyUI.

### Tech Stack

| Layer       | Tech                                   |
|------------|----------------------------------------|
| Backend    | Node.js, Express, Socket.IO, JWT        |
| Database   | MongoDB (Atlas or local)                |
| Frontend   | React, Zustand, Socket.IO client        |
| UI Styling | TailwindCSS + DaisyUI                  |


### Features:

*   Authentication && Authorization with JWT
*   Real-time messaging with Socket.io
*   Online user status (Socket.io and React Context)
*   Global state management with Zustand
*   Error handling both on the server and on the client

### Prequisites
Make sure you have the following installed:
- Node.js (v14+)
- npm or yarn
- MongoDB (local or Atlas)

### Setup .env file inside `backend/` with

```js
PORT=5000
MONGO_DB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```


### Run Backend Server
```shell
npm run dev
```


### Start Frontend
```shell
npm start
```
This will start the server at http://localhost:3000.
