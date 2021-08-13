# AdvancedControls 
An update of OrbitControls in three.js. 

## Introduction
This set of controls performs Rotating, dollying (zooming for OrthographicCamera), and panning.

***Pan up / down / left / right*** - right mouse, or WASD keys / touch: three finger swipe

***Move forward / backward*** - mousewheel or WASD keys / touch: two finger spread or squish

***Rotate*** - middle mouse, or arrow keys / touch: one finger move

## Updates compared to OrbitControls:
1. The dollying of PerspectiveCamera is replaced with panning forward and backward. Therefore, this component can be used to move the PerspectiveCamera to six directions including forward, backward, up, down, left and right from current perspective.
2. Rotation is centered on the camera itself by default. If the target is set, the rotation will be centered on the target.

# CameraControls 
A simplified version of AdvancedControls, but not target of rotation. 

