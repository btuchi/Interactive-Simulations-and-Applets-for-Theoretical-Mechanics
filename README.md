# Interactive-Simulations-and-Applets-for-Theoretical-Mechanics
# Summer '22
# Instructed by Assistant Professor Brain Shuve
# Implemented by Kanalu Monaco & Bryce Tu Chi

See the trajectory.js file for very well-commented code that will hopefully help introduce you to how we built these applets.

To make graphs and animations in JavaScript, we used SVG (scalable graphics vector) and CANVAS elements
SVGs images are created using parameterized curves and are sharp no matter how zoomed in you are, 
but they cannot handle as much data as a canvas.
A canvas draws pixel by pixel and is suited to handle lots of image data.
We used SVGs for graphing smooth curves (with the help of the library d3) 
and canvases for creating animations of physical systems.
You can also look at the HTML file to see where the canvases are.
