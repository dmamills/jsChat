jsChat
=======

a simple node/websockets chat

### Features
* requires login (sqlite3 database)
* websockets real-time chat
* very minimal design, as responsive as a cat when you're within 10 ft of its bag of food

### Install

1. add files to some directory on your server [node must be installed](http://nodejs.org/download/).

2. go into the jschat directory and install dependencies by running: <code>npm install</code> (dependencies: express, socket.io, sqlite3)

3. to start chat server, run <code>npm start</code>

4. direct your browser to <code>localhost:3000</code>. If you want to use something other than localhost, change it in <code>/public/js/jschat.js</code> and if you change the port number update in that and <code>/app.js</code>.

### Notes 

1. if you are running for the first time, <code>jschat.db</code> will be created with a user <code>{ nickname: root, password: root}</code>

2. works on browsers that support [socket.io](http://socket.io/#browser-support)

### Just a big fat FYI

1. this is a learning project for me - basically it is the first time I've ever worked with node, socket.io, express, and sqlite3 all together on my own. it's my precious agile hack job baby in progress

2. this has not been tested beyond my own machine

3. if you have suggestions and tips, please PLEASE [post an issue](https://github.com/jennschiffer/jsChat/issues) or reach out to me <jenn@pancaketheorem.com>. I'd love to get some insight and feedback from those of you who are experienced with these technologies

### To-do List

see TODO.md
