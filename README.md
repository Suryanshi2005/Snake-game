# Snake-game
This repository contains a Snake game developed in Python using the Turtle library. The game allows players to control a snake to collect food and grow in size. The project was created as part of an industrial training program. It is simple and beginner-friendly, showcasing basic game mechanics and Python programming skills.
1. Project Title: "Snake Game"
2. Description:-
   
"This project is a classic Snake Game created using Python and the Turtle graphics library. The objective is to control the snake, eat the food, and grow without hitting the walls or the snake's own body. The game gets progressively harder as the snake moves faster with each meal."

3. Features:-

Snake moves using the keyboard (W, A, S, D).
The snake grows longer after eating food.
The game tracks both the current score and the high score.
The snake's speed increases as more food is eaten.
The game resets if the snake hits the walls or itself.

4. How to play 
"Use the following keys to move the snake:
W: Move Up
S: Move Down
A: Move Left
D: Move Right
Avoid hitting the walls or the snake's body. Try to eat as much food as possible to increase your score.

5. Technologies Used:-
Turtle graphics (for the game interface)

6.Code Explanation
-> Importing Libraries
  turtle: For drawing the snake and food, and managing movement.
  time: To control the speed of the game by adding delays between movements.
  random: To generate random positions for the food.
-> Main Game Elements
   Snake's Head: Created using the turtle module, it starts at the center and moves based on player input.
   Food: A red circle that appears randomly, which the snake eats to grow.
   Scoreboard: Displays the current and highest scores at the top of the game window.
-> Game Logic
   Movement: The snake moves up, down, left, or right based on key presses. The speed of movement increases as the snake eats more food.
   Collisions:
   Wall Collision: If the snake hits the wall, the game resets.
   Self Collision: If the snake runs into itself, the game resets.
   Eating Food: When the snake eats food, its body grows, and the score increases.
-> Additional Features
   Growing Body: Each time the snake eats food, a new segment is added to its body.
   Increasing Speed: As the snake grows, the delay between movements decreases, making the game more challenging.

