# MG6

### MG6 Devlog


1. I believe the loop must iterate completely before the update method finishes because the method activates any code inside its body and lets it run before updating itself on the next frame. So, a long for loop it would cause the game to lag because the update method must run the loop to completetion every frame before it can update again.


2. One issue with our logic is it doesn't check to see what is a platform vs what is a wall which makes it possible to jump through walls. Since both the platforms and the walls are part of the ground layer. To fix it I would need to make the ground and the wall seperate layers. 

