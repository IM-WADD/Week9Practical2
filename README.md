# Practical 19 (W10 Practical 1): The HTML5 Canvas and Libraries
You can treat this practical as a choose-your-own-adventure depending on your interests and your goals for assessment 2. Stage 1 focuses on drawing shapes with the HTML5 canvas element. Stage 2 guides you through a basic clone of the classic game, Snake. Stage 3 includes tutorials on some of the libraries that are allowed for assessment 2, including how to create your own webcam video background using Tensorflow.js. Even if you don't plan on using libraries for assessment 2, you are encouraged to come back to these exercises at a later date as libraries are a fundamental part of web development.

Contents:
- [Stage 1 - drawing with the canvas](#stage-1)
- [Stage 2 - Snake clone](#stage-2)
- [Stage 3 - Library tutorials](#stage-3)

## Stage 1
These drawing-focused canvas exercises will make you nostalgic for the first few weeks of PDM :) They will also help you to get to know the drawing features of the canvas API, beyond what we covered in class.

### 1.1: Draw an alien
As always, create an HTML, CSS, and JS file and link the CSS and JS to your HTML. You will use these files for the rest of the exercises in this stage.

In your HTML, add a canvas element and give it an id. Set its width to 600px and its height to 400px. In CSS, give the canvas a background colour or a border so that you can clearly see its edges. 

In your JavaScript file, create the variables that you will need to work with the canvas:

```
const canvas = document.getElementById(“your-canvas-id”);
const ctx = canvas.getContext(“2d”);
```
Write some code to draw an alien using rectangles, lines, and arcs. Refer to the lecture slides and the reference: [https://www.w3schools.com/tags/ref_canvas.asp](https://www.w3schools.com/tags/ref_canvas.asp). You will need the reference for the remaining exercises.

### 1.2: Try different fill styles
You have probably already used solid fill colours for your alien. Try adding a linear gradient to the background of your canvas to make is look like the night sky. Do this using the canvas API, not CSS.

Add a moon to your canvas which uses a radial gradient as the fill.

### 1.3: Add some text
Give the alien a speech bubble that contains a message. Try using `strokeTextz (rather than `fillText`) with different `strokeStyles` to explore different text effects.

### 1.4: Add animation
Add animation to your canvas drawing. For example, you could:
- Animate the text so it looks like the alien is talking to the user
- Add some mouth movements to the alien as they talk
- Make the alien fly around the scene
- Make the alien wave

## Stage 2
The canvas is most useful for creating animations rather than static drawings. For this reason, this stage focuses on animating the canvas and working with user input while the drawings themselves are kept quite simple. 

To practice animation with the canvas, you will create a simplified version of [Snake](https://www.mathsisfun.com/games/snake.html). There is a video of the completed game in the practical materials. There are LOTS of Snake implementation tutorials available online, but they generally tell you exactly what code to use, which is not always a great way to learn. The following exercises provide guidance but require you to actively apply your knowledge from this module and your previous modules.

### 2.1: Draw and animate a basic snake

## Stage 3
