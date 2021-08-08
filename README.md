# CameraControls 
An update of OrbitControls in three.js. 

## Introduction
This set of controls performs turning, dollying (zooming), and panning.

***Pan up/down/left/right*** - middle mouse / touch: one finger move

***Move forward/backward*** - mousewheel / touch: two finger spread or squish

***Turn*** - right mouse, or arrow keys / touch: three finger swipe

## Updates compared to OrbitControls:
1. The dollying of PerspectiveCamera is replaced with panning forward and backward. Therefore, this component can be used to move the PerspectiveCamera to six directions including forward, backward, up, down, left and right from current perspective.
2. The turning will be conducted using the PerspectiveCamera as the center.


