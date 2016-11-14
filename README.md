Pointing Cloud App
==================
Author: Erik Jan de Wit, Corinne Krych   
Level: Intermediate   
Technologies: JavaScript, socket.io, express.
Summary: A demonstration of how to use socket.io, express.   
Community Project: [Feed Henry](http://feedhenry.org)    
Source: https://github.com/RHMAP-Sample-Mobile-Apps/pointing-cloud  
Prerequisites: node 4+   

## What is it?

This application works with [Pointing Cordova App](https://github.com/RHMAP-Sample-Mobile-Apps/pointing-cordova-app). Different version of the app exist for other platform like [pointing-dotnet-app](https://github.com/RHMAP-Sample-Mobile-Apps/pointing-dotnet-app).

## Build instructions

Install:
```bash
$>npm install
```

Start the server with:

```bash
$> node app.js
```

For testing there are some scripts in `test` one to post a new session and a WebSockets client that
will get notified of the created session.

```bash
$> node client.js
```

```bash
$> node post.js
```