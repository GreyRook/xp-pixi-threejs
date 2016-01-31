# xp-pixi-threejs
Experiment using three.js inside pixi

## Idea / Software Architecture
1. A new class in pixi (inheriting from display object) called ThreeJSObject
2. hook into the rendering of pixi for both WebGL as well as canvas renderer to use three.js to renderer the ThreeJSObject
3. Create the following example with the ThreeJSObject: http://threejs.org/examples/#canvas_geometry_panorama

## Notes
1. ThreeJS should render inside the current canvas and not a second canvas.
2. Embed ThreeJS as object into pixi js - not the other way around

## Sources / references
1. http://www.html5gamedevs.com/topic/20183-simple-quad-with-custom-shaders/#comment-114666
