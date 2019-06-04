# slack-js

This is a messaging channel app created using Javascript and it uses the socket.io api. It has following features:

1. It has 3 different namespaces which have different rooms.
2. Each individual can connect to a room and start chatting there with other clients accessing the same room.
3. It dynamically updates the number of current users in a room as & when a user joins or leaves a room.
4. During startup at client side, you can provide a username which will keep tract of who has sent which message.

# usage
Clone this repository and open cmd/terminal

Go to project directory and do

npm install

nodemon slack.js

Now open the url http://localhost:9000/chat.html in browser and use this chat application after entering your username in the prompt.
