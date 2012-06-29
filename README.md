OpenDepth—Extending the Web
=========

OpenDepth is a client server application that brings Kinect SDK methods and data to the web.
The server is written on C# and built on top of Kinect SDK 1.5,
The client is a written in JavaScript and uses the briliant <a href="https://github.com/mrdoob/three.js/">Three.js</a>webGL rendering engine.

## Features: ##
### Skeleton Tracking ###
Live stream multiple skeletons joints position data (X,Y,Z) including quaternion joint rotation.

### Point Cloud ###
RGBDepth data for a 640X480 rezolution "snapshot" taken with Kinect. 307200 vectors are sent from Kinect to the browser via HTML5 WebSocketss.

## Instalation: ##
+ Download anf install Kinect SDK from http://www.microsoft.com/en-us/kinectforwindows/develop/developer-downloads.aspx. Make sure that your Kinecct camera is installed properly by running one of the SDK demos 
+ Run OpenDepth.exe from build/server
+ Open index.html from build/client into a modern browser
When the server and client are connected a "Connection successful." message will appear on console.

## Requirements: ##
+ Windows 7
+ Kinect SDK
+ Modern browser that supports webGL and WebSockets.
There are 2 prerecorded demos that you can run without without a Kinect on any OS

## Cool things to come: ##
+ Request/Send API
+ Custom multiple touch zones, turn any surface into a touchscreen
+ Making the server as a browser extension
+ Skeleton and point cloud data recording and saving
+ Mesh creation from point cloud
+ Face tracking
+ Rigged 3d characters
+ Iterative Closest Point algorithm for 3d objects scan 
+ More Kinect SDK methodes and data exposed

## About: ##
Point cloud data can lead to exiting new application from gaming to interactivity.
Oppening this kind of data to the web, in our vision, will extent the web, adding a new level of interconectivity.
Unfortunatly Microsoft Kinect is a pretty closed sistem. Our goal is to make this gap smaller and bring this beautifull technology closer to the web.
Some things we would love to see built are web games, augumented reality, scanning and meshing or video mapping.

This code is part of a 24 hours hackatlon. We cut many corners and neglect proper testion. The server will also be relised as an open source once we clean it up.
Made with pride by <a href="https://twitter.com/KatePfau">Ecaterina Paun</a>, <a href="https://twitter.com/alpenzoo">Narcis Paun</a> and 
<a href="https://twitter.com/mirceadesign">Mircea Piturca</a>. Follow the development on <a href="https://twitter.com/odepth">Twitter</a>. Stay in touch at http://opendepth.net/.
Support us by saying hi.
