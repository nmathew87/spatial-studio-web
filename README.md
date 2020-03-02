# Spatial Studio Web

Spatial Studio web is a a placenote frontend module that allows for viewing of Placenote meshes in the browser. Web 3D rendering is accomplished using [THREE.js](https://threejs.org/), a popular web 3D framework. Interaction with the mesh is made possible with the Placenote Web API.

The Placenote Web API enables:
* Viewing or downloading the world mesh as an OBJ file
* Providing raycast based hit testing on the world mesh 
* Writing data to Placenote meta data store 


## How to test this repository

* Close this repository
* Set up a local webserver. You can use [Webserver For Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)
* Open the webserver and define your root repo
* Open localhost. This will load index.html
* Now you can enter an API Key and MapId and click "ViewMesh"