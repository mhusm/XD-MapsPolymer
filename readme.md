# Cross-device Gallery

There are two versions of the gallery example. The first one uses photos stored on the server (gallery.html).
The second one allows the user to choose photos from their device and sends no data to the server (galleryp2p.html).
Additionally, in the first one, the devices communicate via the server, while in the second is configured to use hybrid communication and thus uses peer-to-peer communication where supported.

## Installation
This project requires [node.js](nodejs.org) and [bower](bower.io). In a console, run the following commands in the root of the project.


1. `npm install`
2. `bower install`

## Starting
For the client-server version:

1. `node gallery-polymer.js`
2. Point your browser to http://hostname:8082/gallery.html
3. Share the URL that is displayed in your browser with another device.

For the peer-to-peer version:

1. `node gallery-p2p.js`
2. Point your browser to http://hostname:8082/galleryp2p.html
3. Share the URL that is displayed in your browser with another device.

## Configuration
You can add your own photos to the image folder, just use the same folder structure as the example albums.

