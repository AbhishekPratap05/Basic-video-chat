## Basic Video Chat App
### This is based on YouTube 📹 tutorial by **Web Dev Simplified**- [How To Create A Video Chat App With WebRTC.](https://www.youtube.com/watch?v=DvlyzDZDEq4)
### Using [expressjs](https://expressjs.com/) to create express server 🖥.
### Using [socket.io](https://socket.io/) to create stream 📶.
### Using [uuid](https://github.com/uuidjs/uuid/blob/HEAD/README_js.md) to create random urls 🔗 for video rooms.
### Using [peerjs](https://peerjs.com/) to generate user Id 👱 to connect to video rooms.

---
## How to run

### **Clone or fork project**
>npm i

### **Install Peerjs globally**
>npm i -g peer

### **Run the express server**
>npm run devStart

*express server start listening at port 3000, so make sure port is free to use. If you wish to change can do so by changing in server.js file*


### **Run peer server**
>peerjs --port 3001 

*peer server start listening at port 3001, so make sure port is free to use. If you wish to change can do so by changing in script.js file*
