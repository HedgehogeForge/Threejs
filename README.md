# Test Cilinders in web
Test with Three.js in html.
The provided HTML script sets up an interactive 3D scene using Three.js, where a cylinder can be dynamically updated and moved based on user input and mouse movements. Here's a summary of the key features:

HTML Structure: The document includes a control panel with input fields for adjusting the cylinder's radius, height, and color.

## Three.js Setup:

A scene, camera, and WebGL renderer are created and configured.
A directional light is added to illuminate the scene.
A standard material and initial cylinder geometry are defined and added to the scene.
## Dynamic Cylinder Update:

The updateCylinder function updates the cylinder's geometry and material based on the input values.
Event listeners are added to the input fields to call updateCylinder whenever the values change.
## Mouse Movement:

The onMouseMove function updates the cylinder's position based on the mouse coordinates.
An event listener is added to track mouse movements and update the cylinder's position accordingly.
## Saving Cylinder Positions:

An array positions is used to store up to three positions of the cylinder.
The onMouseClick function clones the cylinder and saves its position when the mouse is clicked, up to a maximum of three positions.
An event listener is added to track mouse clicks and save the positions.
## Animation Loop:

The animate function continuously renders the scene, ensuring smooth updates and interactions.
The script allows users to interactively modify the cylinder's properties and move it around the canvas, while also saving up to three static copies of the cylinder at different positions when the mouse is clicked.

A picture of the result. Simple but useful for learning.
![image](https://github.com/user-attachments/assets/1400ce62-0e51-4855-b1ad-8a78548a0102)


