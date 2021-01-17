# Good Run

Good Run is a project utilizing tiny-graphics.js to create a scene of a car driving down an infinite road.

![Car Scene](/images/sample.PNG)

## Basic Features
* Utilization of translation, scaling, and rotation matrices to control movement of most objects in the Scene
* imported blender models and textures for the car, coins, off-road objects, and backgrouund images
* WASD controls for steering, acceleration, and deceleration
* Score count for each coin collected

## Advanced Features

* Collision Detection
  * Basic collision detection of off-road object and collectible coins
* Texture/Bump mapping
  * Texture mapping to simulate movement of the ground, street, and sky
  * Custom phong reflection on the car
  * Bump mapping to provide roughness to the street and ground
  * Naive implementation of shadow beneath the car
  
 ## To Run
 Clone this repo and run either host.bat or host.command depending on your platform.
 
 ## To Play
 Steer the car left/right using A/D. Accelerate using W, decelerate using S. Collect coins to increase your score counter. Sit back and enjoy the aesthetic as you travel down an infinite road under a changing sky.
