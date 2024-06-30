# Snake Game:
### Hosted Link: https://divyanshrajpoot9.github.io/Snake_Game/
### Technologies Used: HTML5/CSS3/JavaScript/ES6/Git/GitHub/VsCode/MongoDB/MySQL/Figma/FontAwesomeCDN/BootStrap.
This code is a JavaScript implementation of the N-Queens problem visualization using HTML, CSS, and JavaScript. 
Here's a breakdown of the code:

# 🎮 SnakeMania - Ek Gaming Katha 🎮

Welcome to SnakeMania! 🐍

SnakeMania - Ek Gaming Katha is an engaging and modern twist on the classic Snake game, reimagined to provide an exhilarating gaming experience right in your browser. Whether you're here to relive nostalgic moments or looking to enjoy a quick gaming break, SnakeMania is the perfect choice for you!
🌟 Features

    🎮 Intuitive Gameplay: Enjoy seamless and addictive gameplay that captures the essence of the classic Snake game.
    🌈 Modern Design: Experience vibrant visuals and smooth animations designed to keep you entertained.
    📈 Dynamic Scoring: Track your progress with real-time updates to your score and high score.
    📱 Responsive Design: Play SnakeMania effortlessly on any device – desktop, tablet, or mobile.

🚀 Getting Started:

<!DOCTYPE html>: Declares the document type and version of HTML.
<html lang="en">: Specifies the language of the document as English.
<head>: Contains meta-information about the HTML document.

    <meta charset="UTF-8">: Sets the character encoding to UTF-8.
    <meta http-equiv="X-UA-Compatible" content="IE=edge">: Instructs Internet Explorer to use the latest rendering engine.
    <meta name="viewport" content="width=device-width, initial-scale=1.0">: Ensures the website is responsive on different devices.
    <title>SnakeMania - Ek Gaming Katha</title>: Sets the title of the web page.
    <link rel

        ="stylesheet" href="css/style.css">: Links the CSS file for styling.
    <body>: Contains the visible content of the web page.
        <div class="body">: Wraps the main game elements.
            <div id="scoreBox">Score: 0</div>: Displays the current score.
            <div id="hiscoreBox">HiScore: 0</div>: Displays the highest score.
            <div id="board"></div>: The main game board where the snake will move.
    <script src="js/index.js"></script>: Links the JavaScript file for game logic.
    
## CSS:
body: Centers the game elements on the page and sets a neutral background color.

    margin: 0;: Removes default margin.
    font-family: Arial, sans-serif;: Sets the font.
    display: flex;: Uses flexbox for layout.
    justify-content: center; align-items: center;: Centers content horizontally and vertically.
    height: 100vh;: Sets the height to the full viewport.
    background-color: #f0f0f0;: Sets a light gray background.

.body: Centers the text within the game container.
    text-align: center;: Centers the text.

#scoreBox, #hiscoreBox: Styles the score and high score boxes.
    font-size: 20px;: Sets the font size.
    margin: 10px;: Adds space around the elements.
    color: #333;: Sets the text color.

    #board: Defines the game board's appearance.
        width: 400px; height: 400px;: Sets the size.
        background-color: #fff;: Sets the background to white.
        border: 2px solid #333;: Adds a dark border.
        position: relative;: Allows positioning of elements inside the board.
        margin: 20px auto;: Centers the board and adds margin.

## JavaScript:
    Event Listener: The script runs once the DOM content is fully loaded.
    Element References: board, scoreBox, and hiscoreBox are references to the game board and score displays.
    Initial Variables: Initializes score, hiscore, snake's initial position, food's position, and movement direction.
    gameLoop(): Updates the game state by moving the snake, checking for collisions, and rendering the new positions.
    moveSnake(): Moves the snake

Follow these steps to run SnakeMania locally on your machine:

Alternatively, you can play the game online here.
🛠️ Built With

    HTML5 & CSS3: For a sleek and modern design.
    JavaScript: For the core game logic and interactivity.

🖥️ Project Structure

plaintext

SnakeMania/
│
├── css/
│   └── style.css        # Main stylesheet for the game
│
├── js/
│   └── index.js         # Main JavaScript file containing game logic
│
├── index.html           # Main HTML file for the game
│
└── README.md            # Project description and details

💡 How to Play

    Move the Snake: Use arrow keys on your keyboard.
    Objective: Guide the snake to eat the food, grow longer, and avoid colliding with the walls or itself.

📷 Screenshots:
![image](https://github.com/divyanshrajpoot9/Snake_Game/assets/114856467/4a68a6a2-1c23-4d16-a966-09d8ef1c0652)





