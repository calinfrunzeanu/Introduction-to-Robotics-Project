<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Videogame Console Project</title>
</head>
<body>
  <h1>Videogame Console</h1>

  <h2>Introduction</h2>
  <ul>
    <li><strong>What it does:</strong> This project is a videogame console that allows users to play classic games.</li>
    <li><strong>Purpose:</strong> To create a retro-inspired gaming experience using simple hardware and custom programming.</li>
    <li><strong>Idea behind it:</strong> The idea originated from the desire to combine classic games with the challenge of building an embedded system that interacts with both hardware and software.</li>
    <li><strong>Why it’s useful:</strong> The project offers an engaging and interactive way to explore game design, electronics, and programming, and serves as a fun and educational experience for both the developer and end users.</li>
  </ul>

  <h2>General Description</h2>
  <p><strong>Block Diagram of the Project:</strong></p>
  <ul>
    <li><strong>Hardware Modules:</strong>
      <ul>
        <li><strong>LED Matrix:</strong> Displays the active game in real-time.</li>
        <li><strong>LED Display:</strong> Shows the main menu for selecting a game and, during gameplay, displays the score and additional functionalities.</li>
        <li><strong>Buttons:</strong> Navigate the menu and control the games.</li>
        <li><strong>Microcontroller (e.g., Arduino Uno):</strong> Acts as the brain of the system, controlling the game logic and interfacing with the hardware.</li>
      </ul>
    </li>
    <li><strong>Software Modules:</strong>
      <ul>
        <li><strong>Game Engine:</strong> Contains the logic for Snake, Tetrix, and Pong.</li>
        <li><strong>Menu Navigation System:</strong> Allows users to select the desired game and view information.</li>
        <li><strong>Scoring System:</strong> Tracks and displays scores for each game.</li>
      </ul>
    </li>
  </ul>
  <!-- TODO: Add a block diagram image -->
  <p><img src="images/block_diagram_console.png" alt="Block Diagram" /></p>

  <h2>Hardware Design</h2>
  <p><strong>List of Components:</strong></p>
  <ul>
    <li><strong>Microcontroller:</strong> Arduino Uno</li>
    <li><strong>8x8 LED Matrix</strong></li>
    <li><strong>7-Segment LED Display</strong></li>
    <li><strong>Buttons (x4):</strong> Up, Down, Select, Reset</li>
    <li><strong>Power Source:</strong> 5V adapter or USB</li>
    <li><strong>Additional Components:</strong> Resistors, jumper wires, breadboard</li>
  </ul>
  <!-- TODO: Add electrical schematics -->
  <p><img src="images/electrical_schematic_console.png" alt="Electrical Schematic" /></p>

  <h2>Software Design</h2>
  <ul>
    <li><strong>Development Environment:</strong> Arduino IDE</li>
    <li><strong>Libraries Used:</strong>
      <ul>
        <li><code>Adafruit_GFX.h</code> and <code>Adafruit_LEDBackpack.h</code> for controlling the LED matrix and LED display.</li>
        <li><code>Bounce2.h</code> for button debouncing.</li>
      </ul>
    </li>
    <li><strong>Algorithms and Structures:</strong>
      <ul>
        <li>Game Logic: Implemented state machines for Snake, Tetrix, and Pong.</li>
        <li>Menu Navigation: Uses button inputs to cycle through games and settings.</li>
        <li>Scoring System: Real-time score updating and display integration.</li>
      </ul>
    </li>
    <li><strong>Functions Implemented:</strong>
      <ul>
        <li><code>setupMenu()</code>: Initializes the main menu.</li>
        <li><code>startGame(gameType)</code>: Launches the selected game.</li>
        <li><code>updateDisplay(score)</code>: Updates the LED display with the current score.</li>
      </ul>
    </li>
  </ul>

  <h2>Results Obtained</h2>
  <p><strong>Functionality:</strong></p>
  <ul>
    <li>Successfully displays games on the LED matrix.</li>
    <li>Smooth menu navigation.</li>
    <li>Real-time score updates on the LED display.</li>
  </ul>
  <p><strong>Game Features:</strong></p>
  <ul>
    <li>Fully playable versions of Snake, Tetrix, and Pong.</li>
    <li>Adjustable difficulty levels for Snake and Pong.</li>
  </ul>

  <h2>Conclusions</h2>
  <p>This project successfully combines hardware and software to create an engaging retro gaming experience. It demonstrates the potential of embedded systems in interactive applications. The console is portable, cost-effective, and provides a solid foundation for further development and customization.</p>

  <h2>Source Code and Other Resources to Include on GitHub</h2>
  <p><strong>Suggested Directory Structure:</strong></p>
  <ul>
    <li><strong>src/</strong>: Contains source code for the project.</li>
    <li><strong>hardware/</strong>: Includes electrical schematics and diagrams.</li>
    <li><strong>images/</strong>: Stores all visuals (block diagrams, schematics, demo photos).</li>
    <li><strong>README.md</strong>: This document.</li>
  </ul>

  <h2>Demo Video</h2>
  <!-- TODO: Add a demo video link -->
  <p>Embed your video link here (e.g., <a href="#">YouTube Demo Video</a>).</p>

  <h2>Journal</h2>
  <!-- TODO: Add progress tracking details -->
  <p>Add a section to document progress, including dates, milestones, and any challenges encountered during the development process.</p>

  <h2>Bibliography/Resources</h2>
  <ul>
    <li><strong>Software Resources:</strong>
      <ul>
        <li><a href="https://github.com/adafruit/Adafruit_LED_Backpack" target="_blank">Adafruit LED Backpack Library</a></li>
        <li><a href="https://github.com/thomasfredericks/Bounce2" target="_blank">Bounce2 Button Library</a></li>
      </ul>
    </li>
    <li><strong>Hardware Resources:</strong>
      <ul>
        <li><a href="https://www.arduino.cc/" target="_blank">Arduino Uno Datasheet</a></li>
        <li><a href="https://example.com/led-matrix-doc" target="_blank">8x8 LED Matrix Documentation</a> <!-- TODO: Replace with correct link --></li>
      </ul>
    </li>
  </ul>
</body>
</html>
