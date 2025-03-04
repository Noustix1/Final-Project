Project Title: Fire Out

Video Demo: https://youtube.com/shorts/PSGOeFhW3MM?feature=share

Description: Video game where you play as a flame dodging raindrops

Fire out is an interactive, rapid game where the player is the red triangle representing a flame. To win the game, the player must avoid all the blue raindrops. Once the game has begun there are blue raindrops that were created to fall from the top of the screen, if there is a collision with the raindrop and the flame; in this case the player then the game is over. To avoid the blue raindrops, you can move left or right with your arrow keys on your computer keyboard to avoid the blue raindrops as they fall from the top of the screen. After the game is over, the player can see how long they have survived in the game and then choose if they would like to restart the game and beat their highest score. The goal for this game was to create an interactive, but also simple game using Pythons turtle library. Our main priority was to make a fun game while also developing the logic behind the game, which in this case are the mechanics, collision detection, raindrops randomly falling, and a couple of dynamic difficulty adjustments. This project gave us the opportunity to display our python programming skills to make a fun game. 

Step one in coding “Fire Out” was to set up the game window by using Python's turtle module. We used the screen.setup() method to make a 600x600 pixel game window. The player is the red triangle which was created by using the turtle.turtle() method. The player starts in the center of the bottom of the screen which we set by using the player.goto() method. There are multiple mechanics behind the game, but the main mechanic is the arrow key functions being that it is the key you need to use to play the game. The arrow keys that point left to right are used the most by the player. Since the blue raindrops are randomly generated to fall from the top of the screen to the bottom of the screen at an array of different speeds, which adds a challenge element to the game's level of difficulty. The actual movement of the red triangle when pressing those arrow keys was created by using the onkeypress method. By using that, we could assign the left and right arrow key to horizontally move across the bottom on the screen. The most difficult part of that was ensuring the keys moved smoothly across the bottom of the screen to give the player the best chance of lasting in the game. When a blue raindrop hits the red triangle, the game automatically stops, and you are shown how long you lasted in the game from start to finish. 

After finishing the coordination of the flame, represented by the red triangle we moved our focus to the blue raindrops. To make the blue raindrops fall from the top of the screen we created a function; create_raindrop() which is what generates the raindrops. Use of the random.randint() function is what made it possible to randomly place the raindrops along the x-axis. The most important part of the game is the collision factor; when the blue raindrop hits the red triangle because this is when you know the game is over. For the game to detect when a raindrop collides with the flame, we used the player.distance(raindrop) method. This calculates the distance between the player and the raindrop. If this distance is smaller than 20 pixels it triggers the end of the game. Once the raindrop and flame collide it displays a game over with the time that the player stayed in the game, and we did that by setting a game over flag to true. This is a loop that makes the player easily understand when the game is over. 

In conclusion, this project allowed us to take games we have enjoyed and use them as inspiration to make a version of our own. It has also helped us strengthen our python and collaborative skills that we have been working on throughout core module three. We are looking ahead and hoping to expand by adding things like levels that become more challenging, in each level adding a new object. songs, and more elements to the game to enhance the user's experience. We plan to do this by adding a sound when the raindrop and flame collide. Minor edits like this will make the game more addictive and challenging. This small, fun, simple game has expanded our thinking and coding skills. 
