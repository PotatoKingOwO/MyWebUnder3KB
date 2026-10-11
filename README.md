# Cone Theremin

It is a theremin with a 3D cone visualization.

## How to use it

- Moving the mouse left and right controls pitch, cone width, and color, along with rotation speed.
- Up-and-down movement controls the volume and the height of the cone.
- Holding down the mouse button plays a sound.

## How it works

- The 3D structure is programmed manually - each point calculates its position on a 2D canvas, where they are then connected to form a cone.
- The canvas is rendered using the Canvas API and the audio using the Web Audio API.
