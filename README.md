OpenDepth—Extending the Web
=========

OpenDepth is a client server application that brings Kinect SDK methods and data to the web.
The server is built on top of Kinect SDK 1.5, the client is a written in JavaScript and uses the briliant Three.js webGL rendering engine.

Features:
=========
Skeleton Tracking
Live stream multiple skeletons joints position data (X,Y,Z) including quaternion joint rotation.

Point Cloud
RGBDepth data for a 640X480 rezolution "snapshot" taken with Kinect. 307200 vectors are sent from Kinect to the browser via HTML5 WebSocketss.

