# **Boss Hitbox Information:**
## **Mecha Sonic**

Mecha Sonic has a hitbox whose origin X/Y coordinates are shared with Mecha Sonic's X/Y coordinates.  Its width radius is 16, and its height radius is 27, resulting in a 33 x 55 rectangle.

Mecha Sonic also has 2 damage hitboxes.

The first one is always active, and shares its origin X/Y position with Mecha Sonic's X/Y coordinates.  Its width radius is 12, and its height radius is 12, resulting in a 25 x 25 rectangle.

The second damage hitbox is only active when Mecha Sonic is stationary.  

Its origin is located at ((X ± (width radius of first hitbox)), (Y - (height radius of first hitbox))).  Whether you add, or subtract the X radius to get the origin X pos of this hitbox depends on the direction that Mecha Sonic is facing.

This damage hitbox has a width radius of 4, and a height radius is 4, resulting in a 9 x 9 rectangle.

## **Death Egg Robot**

The Death Egg Robot has 2 hitboxes, one for the robot's torso, and one for the robot's head.

The Death Egg Robot also has multiple damage hitboxes. (2 for each leg, 2 for both arms, 1 for the torso, and 1 for the flame under the Death Egg Robot's engine?).

The bombs that are launched from the back of the robot have a single damage hitbox, which shares its origin X/Y position with the bomb object itself.  Its width radius is 12, and its height radius is 12, resulting in a 25x25 rectangle.

TODO: Add data, as this is a rather complex boss with lots of hitboxes.
