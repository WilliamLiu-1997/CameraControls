# CameraControls 
An update of OrbitControls in three.js. 

[Live Demo](https://rawcdn.githack.com/WilliamLiu-1997/three.js/415adb451216e3cc9c1a8cecb27c0f373e1450f5/examples/misc_controls_cameracontrols.html)

## Introduction
This set of controls performs Rotating, dollying (zooming for OrthographicCamera), and panning.

***Pan up / down / left / right*** - right mouse, or WASD keys / touch: three finger swipe

***Move forward / backward*** - mousewheel or WASD keys / touch: two finger spread or squish

***Rotate*** - middle mouse, or arrow keys / touch: one finger move

## Updates compared to OrbitControls:
1. The zooming of PerspectiveCamera is replaced with dollying forward and backward.
2. Rotation is centered on the camera itself by default. If the target is set, the rotation will be centered on the target.


