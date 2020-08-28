# backend-chat-application-socket-io

This is the backend code base for a real time chat application built with socket.io & node.js.

Join virtual chat rooms and share messages among other members of the room. Simply type in your name/nick-name/preferred-name along with the room name you want to join to get access to the room and you are good to go. If you want to create a room simply follow the same steps and if a room is not present it will create a new room with the name specified and then share the same across other members whom you want to join the same room.

This chat application extensively uses socket.io library to establish socket connection between client and the server for real time event based communication.

## What Socket.IO is
Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of: <br />

* a Node.js server
* a Javascript client library for the browser (which can be also run from Node.js)

Official Documentation: https://socket.io/docs/

This chat application support the following features :

0 : This app is responsive with desktop, tablet & mobile compatibility.<br />
1 : Support emojis. Simple type in emoji referencing text like :) and that will be converted to emoji in the chat.<br />
2 : 2 persons with same name wont be allowed to enter the same room. You will get a prompt for the same.<br />
3 : In desktop view you will be able to see all the active members of the room beside the chat box.<br />
4 : In Tablet or Mobile view click on the icon next to Room name on header to see the active members list.<br />
5 : Notification message every time someone new enter the room or if someone leave the room.<br />
6 : Simple & Elegant User Interface.

Both the backend code base and the forntend code base is hosted in Heroku.

Frontend Code Base : https://github.com/abinash-nayak/frontend-chat-application-socket-io

Live Application : https://chat-application-socket-io.herokuapp.com/

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

On Success you will see something like this if you visit http://localhost:5000  : <br />
```json
{"response":"Server is up and running."}
```

The page will reload if you make edits.<br />
You will also see any lint errors in the console.
