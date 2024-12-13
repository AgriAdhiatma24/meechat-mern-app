
# MeeCHAT App | MERN Realtime Chat APP

MeeChat is a real-time, chat application designed to facilitate seamless communication between users. Built with the MERN stack (MongoDB, Express, React, Node.js), MeeChat leverages the power of WebSockets through the Socket.io library to provide fast, interactive, and dynamic messaging experiences.




## Screenshots

![App Screenshot](/frontend/public/ProjectChat_1.png)

Highlights:

- ⭐ Authentication & Authorization with JWT
- ⭐Real-time messaging with Socket.io
- ⭐Global state management with Zustand
- ⭐Error handling both on the server and on the client

## Tech Stack
### Frontend

- React (Vite)
- Javascript
- TailwindCSS
- Daisy UI
- Zustand

### Backend
- MongoDB
- Express.js
- Node.js
- Socket.io 
- Cloudinary
- JWT


##  Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```
## Run Locally

Clone the project

```bash
  git clone https://github.com/AgriAdhiatma24/meechat-mern-app
```

Go to the project directory

```bash
  cd meechat-mern-app
```

Build the app

```bash
  npm run build
```

Start the server

```bash
  npm run start
```

