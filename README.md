

# Game Options

## Option 1. Shooter

For this option, imagine a 2d grid with enemies advancing from all sides. The player moves with wasd and shoots using the arrow keys. Enemies spawn from the north, south, east, and west. The player has three lives, and loses a life when an enemy gets too close, after that it's game over.

- Create a class to represent the **Player**.
    - Implement methods for **shooting** that create Bullet objects.
    - Implement methods for **moving** triggered by the wasd keys.

- Create a class to represent a **Bullet**. 
    - Bullets move in a straight line starting from the player's position when the Bullet is created. 
    - If a bullet touches an Enemy, the Enemy disappears.

- Create a class to represent **Enemies**.
    - Implement a method **move**. Enemies move towards the Player.

## Option 2. Space Invaders

For this option, imagine a grid of aliens. Those on the bottom of the entourage fire shots towards Earth while slowly advancing.

- Create a class to represent the **Player**.
    - Implement methods for **shooting** that create Bullet objects.
    - Implement methods for **moving** triggered by the a and d keys.

- Create a class to represent a **Bullet**.
    - Bullets move in a straight line starting from the player's position when the Bullet is created. 
    - If a bullet touches an Enemy, the Enemy disappears.

- Create a class to represent a **Shield**.
    - Shields can withstand five hits before breaking down.

- Create a class to represent **Enemies**.
    - Implement methods for **shooting** that create Bullet objects.

## Option 3. Match

For this option imagine a grid of cards with one missing. The player selects cards to swap or move. The player's goal is to make a picture, group like colors together, or otherwise put the cards into a specific arrangment

- Create a class to represent a **Card** on the grid.
- Create a class to represent the **Grid** of cards.
- Create a class to represent a **CardMatch** (if applicable).
- Create a class to represent the **Player** (if applicable).

## Option 4. Snake

For this option, imagine a 2d grid for the snake to move through. Apples randomly spawn throughout the map. The player uses wasd to control a snake and collect apples. Each time the snake eats an apple, its length grows by one. If the snake runs into the outmost walls or itself, it's game over.

- Create a class that represents a **SnakePart**.
    - Each SnakePart should store the **next SnakePart** in an instance variable, unless it is the end of the snake.
    - Implement a method **move** which moves the SnakePart to the next space AND calls move on the next SnakePart. The next SnakePart should move to the location of the previous SnakePart.
    - Implement a method **grow** which in a manner similar to move calls grow on the next SnakePart until it reaches the end of the snake. Add a new SnakePart to the end of the Snake by storing it in the previously unused instance variable.
    
- Create a class **SnakeHead** that inherits from SnakePart. This represents the head of the snake.
    - The SnakeHead should have a different color from the rest of the snake.
    - Override the **move** method so that wasd controls the direction the SnakeHead moves

- Create a class **Apple** to represent food for the snake to eat.

## Option 5. Your Own Game!

- Up to you!

# Rubric

2 points - Create a **polished and high-effort game** that reflects your creativity and ability.

3 points - Create at least three substantive classes, **utilizing a class' ability to store both code AND data.**

1 point - Use a variety of sprites incorporating animation, color changes, etc.

1 point - Accept user input to control the user's interaction with the game.

1 point - Use iteration to **drive** the game code.

1 point - Change the parameters (e.g., speed, difficulty) of the game **as it progresses.**

1 point - Display when someone wins or loses the game, or keep track of points

10 POINTS TOTAL
