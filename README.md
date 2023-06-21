**# SnakeGame**
Snake game built using Java and GUI made by using Java swing library. A user can provide directions to the snake using arrow keys and make it eat food. Also if the snake collides with the border or body, the game gets over and score gets displayed to the user.
It icludes two main classes:

-> Snake (extends JFrame and invokes the Board class)
-> Board (extends JPanel)

**The Board class provides following methods:

-> initBoard() - It initializes Board Panel.
-> loadImages() - It loads images of Snake head, Snake body and food.
-> initGame() - It initializes Game.
-> checkCollision() - It checks collision of Snake's head with an obstacle (itself/food/wall).
-> locateApple() - It randomize Apple position every time.
-> gameOver() - It displays Game Over massage and player's score.
-> This game includes the following functionalities:

The player can move the snake left, rigt, up, and down as per the given direction using respective arrow keys.
Whenever the snake eats food, its length increases by one and live score is displayed on screen.
The food appears on random position each time, either when the snake eats one or the new game is started.
When the snake collides with itself or with any of the wall, the "Game Over" massage it displayed along with player's score.
Design elements -

* Represented by green dot is Snakehead.
* Represented by red dot is SnakeBody.
* Represented by an apple is Food.

  **Project Snippets**






  ![image3](https://github.com/GnaneshwariSarala/SnakeGame/assets/137158564/0eaa6293-e38a-4792-8520-8887b59ea15e)
  ![image2](https://github.com/GnaneshwariSarala/SnakeGame/assets/137158564/9b953b2c-6c99-48ed-b078-a9b11598c567)

  
  
  
  

