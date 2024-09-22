# WebGL-Olympic-Rings

This project is an assignment from the Cmput 411 course that utilizes WebGL to create and animate the Olympic symbol. The original assignment was incomplete, and I added code to animate the Olympic rings.

## Features

- **Olympic Rings Animation**: WebGL implementation of the five colored rings representing the Olympic symbol, which rotate and are animated using shaders.
- **Shaders**: Vertex and fragment shaders are used to dynamically calculate the position and color of each torus.
  
![Screenshot](https://github.com/jackie174/Cmput411-A6/blob/master/A6/media/Screenshot%202023-03-25%20134233.png)  
![GIF](https://github.com/jackie174/Cmput411-A6/blob/master/A6/media/Video_2023-03-25_134838.gif)

## Getting Started

### Prerequisites

Ensure you have a browser that supports WebGL and the necessary files in the correct directories:
- **cuon-utils.js**: WebGL utility functions
- **cuon-matrix.js**: Handles matrix operations
- **webgl-debug.js**: Debugging tools for WebGL
- **webgl-utils.js**: Set up and manage the WebGL context

### Files

- `sphere.html`: Main HTML file that initializes the WebGL canvas
- `sphere.js`: The WebGL implementation and shaders for rendering the Olympic rings
- `init.js`: Provides additional setup functions and buffer initialization

### How to Run

1. Open `sphere.html` in a WebGL-supported browser.
2. The Olympic rings will animate automatically upon loading the page.

### Modifications

- Added rotation code for the Olympic rings to animate them smoothly.
- Implemented Phong lighting to enhance the visual quality of the rings.

### References

- `sphere.js` (c) Herb Yang, Oct. 9, 2020, modified from shadertoy.com
