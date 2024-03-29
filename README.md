# microbit projects

A list of open-ended MicroBit projects. Some sources include [bournetocode.com](https://bournetocode.com/projects/7-CS-micro/index.html) and [MakeCode Intro to CS](https://makecode.microbit.org/courses/csintro)


[For Loops](#projects-with-for-loops)

  - [Get Loopy](#get-loopy)
  - [Turn Signal](#turn-signal)
  - [Fade One LED](#fade-one-led)
  - [Travelling Sprite](#travelling-sprite)

[Conditionals](#projects-with-conditionals)
  
  - [Light Sensor Face](#light-sensor-face)
  - [Make A Song](#make-a-song)
  - [Musical Instrument](#musical-instrument)
  - [Blink Three LEDs](#blink-three-leds)

[Variables](#projects-with-variables)

  - [Hot Potato](#clicker-game)
  - [Clicker Game](#clicker-game)
  - [Fade Two LEDs](#fade-two-leds)
  - [Weird Blackjack](#weird-blackjack)
  - [Variable Flashlight](#variable-flashlight)

[While Loops](#projects-with-while-loops)

  - [Running Game](#running-game)
  - [Reaction Time Game](#reaction-time-game)
  - [Bouncing Off The Walls](#bouncing-off-the-walls)
  - [DDR Game](#ddr-game)
  - [Gyroscope Game](#gyroscope-game)

[Projects with Servo Motors](#projects-with-servo-motors)

  - [Robot Arm](#robot-arm)
  - [Droid](#droid)
  - [RC Car](#rc-car)

[Projects in MicroPython](#projects-in-micropython)

  - [MicroPython Speak](#micropython-speak)
  - [MicroPython Sing](#micropython-sing)
  - [MicroPython Neopixels](#micropython-neopixels)


---




---

## Projects with For Loops

---

# Get Loopy

Start by adding a "on button A pressed" block from the Input menu.

Next, add a "show icon" block from the Basic menu.

Next... get loopy!

There are many different ways to use loop blocks. The three types of loop blocks in Microbit are Repeat X Times, While, and For Loop.

How will you use loops to create something useful, entertaining, or interesting? Here are some suggestions:

- Create different animations that loop when different buttons are pressed.
- Create an animated gif (looping image that changes) and add music that matches.
- Create animation that repeats for one of the melodies included in the Music section (like Happy Birthday).
- Create an alarm that includes sound and looping images. What will set the alarm off? What will make the alarm stop sounding?

Reflection

1.  Explain how you decided on your particular “loopy” idea. What brainstorming ideas did you come up with?
1.  What types of loops did you use? (Repeat X Times, While, or For Loop)
1.  What was something that was surprising to you about the process of creating this program?
1.  Describe a difficult point in the process of designing this program, and explain how you resolved it.
1.  Share your project with someone and ask what they liked and what could be improved. What feedback did your "beta testers" give you? How did that help you improve your loop demo?

---
# Turn Signal

Use for loops to make blinking lights.

On button A pressed, a left arrow should blink on and off 3 times. Use a "pause (ms) 100" block within the for loop to slow down the blinking.

On button B pressed, a right arrow should blink on and off 3 times.

On button A+B pressed... MAKE IT YOUR OWN. Maybe blink between two different patterns or faces? Maybe spell out a word one letter at a time?
---

# Fade One LED

Use for loops to adjust an LED from 0 (off) to 255 (full).

Inside of the "on button A pressed" block, add a "for index in 0 to 4" loop. From the LED menu, click More and get a "plot x 0 y 0 brightness 255" block. Use the index variable to gradually fade the LED brightness from 0 up to 255.

Include a "pause (ms) 100" block within the for loop to slow down the fade. Use a very small pause like 10.

On button B pressed, gradually fade the brightness from 255 down to 0.

On button A+B pressed... MAKE IT YOUR OWN. Maybe set one random LED to a random brightness? Maybe set all LEDs to either 255 or 0? Maybe loop 255 times setting a random LED to a random brightness? Maybe clear the screen?

---

# Travelling Sprite

Drag the repeat block to the coding Workspace. Notice that this block takes a parameter. A parameter is a type of variable used as input to a function or routine. In this case, the parameter tells the repeat block how many times we want the code within the block to repeat. For now, we’ll leave the parameter at 4.

For this project, you can delete the default ‘forever’ block.

To create a sprite that will walk around the Microbit matrix:

- Click on the Advanced category in the Toolbox. This will open up a more advanced menu of blocks.
- Click on Game category, and drag a ‘create sprite’ block to the coding workspace.
- We’ll need two more blocks from the Game menu.
  - Drag out a ‘move by’ block and a ‘turn right by’ block. They now have these blocks in their coding workspace.
- From the Variables menu, drag a 'set sprite to 0' block to the coding workspace.

Next, let's start combining the blocks. On Start, set sprite to create sprite at x 2 y 2.

From the Input menu, drag out a 'on button A pressed' block. Also, get a 'on button B pressed' block and get a 'on pin P2 pressed' block.

Decide which button moves the sprite forward. Use the "repeat 4 times" block to move the sprite forward. 

MAKE IT YOUR OWN: Which button should turn the sprite? Can the sprite turn in the opposite direction? Can the sprite move backwards?

When finished, show your teacher which commands you have mapped to which buttons.

---

## Projects with Conditionals

---

# Light Sensor Face

This project will use the built-in light sensor (built into the LEDs). The "light level" variable can be found in the Input menu. On button A press, show a happy face if it is bright and a sad face if it is dark. 

Now, let's make a fidget cube out of the micro:bit. MAKE IT YOUR OWN: Create a unique output for each of the following inputs:

- on button B pressed
- on button A+B pressed
- on pin P0 pressed
- on pin P1 pressed
- on pin P2 pressed
- on shake

---

# Make A Song

Attach a speaker.

Create a variable and set it to false

In the forever loop, write code that plays your sounds (8 or more notes) if a variable is set to true

When the A button is pressed, set the variable to true

When the B button is pressed, set the variable to false

---

# Musical Instrument

Create a musical instrument. Attach a speaker.

When the A button is pressed, play a Low A note.

When the B button is pressed, loop through these notes: C, D, E, G, A

There are multiple ways that the B button could work...

- The B button could randomly play either C, D, E, G, A
- The B button could play C on the 1st press, then D on the 2nd press, etc.

MAKE IT YOUR OWN: Decide what happens on pin P0 pressed, on pin P1 pressed, and on pin P2 pressed.

---

# Blink Three LEDs

Use the "toggle x 0 , y 0 " block to blink two or three different LEDs on the Microbit.

You may want to add "pause (ms) 100" blocks between each toggle block.

Your first LED might be x: 1 and y: 1. Your second and third LEDs should have different coordinates.

When A is held down blink two LEDs in a pattern like this 1-2-1-2-1-2-1-2

When B is held down blink three LEDs in a pattern like this 1-2-3-1-2-3-1-2-3

When button A+B is pressed... MAKE IT YOUR OWN! Make up your own pattern.

---

## Projects with Variables

---

# Hot Potato 

Players pass the Microbit from one to another. Every 5-20 seconds (at random), the Micro:bit should change image, play a sad sound, and that player is out. The game then continues until there is only one player left.

Start by asking "How Many Players?"

Use A and B buttons to increase decrease the number of player.

Press A+B to start the game. 

Use a for loop to repeat for the correct number of rounds.

---

# Clicker Game

Player A will be clicking the A button as quickly as possible. Player B will be clicking B button as quickly as possible. Highest score wins.

1.  Create a timer variable and set it to 5 (or 9).

1.  Create a score variable (or two) and set it to 0.

1.  Countdown from 5 to 0, displaying the timer on the "screen"

1.  When button A is pressed player A gets points. When button B is pressed player B gets points. MAKE IT YOUR OWN: Increase the amount of points over time. Maybe each click doubles your score? Maybe the timer changes your score so that clicks when the timer begins are worth fewer points and then clicks when the timer is low are worth more points? Maybe the player with fewer points earns a bonus point for each click?

1.  When the timer is zero or less, say who wins... either player A or player B.

---

# Fade Two LEDs

You will use a variable and loops to adjust the LED from 0 (off) to 255 (full).

Gradually fade the LEDs from 0 up to 255, then down to 0, then up to 255, then down to 0, then up to 255, etc

The 2 LEDs should be out of sync with each other so that one is at 0 while the other is at 255.

---

# Weird Blackjack

MSCoding Weird Blackjack (variables)

Blackjack is a multi-player card game also known as “21” in which you are trying to get close to a total of 21 points without going over.
Weird Blackjack is a single player game that you will make for Microbit. Everyone’s game will be unique.

1.  You will need a variable to store the player’s score which could start at 1 or some random number (your choice).
1.  If the player presses the A button it increases the player’s score (either adds a random amount to their score or it multiplies their score, your choice). 
1.  If the player presses the B button it decreases the player’s score (either subtracts a random amount from their score or it divides their score, your choice).
1.  If the player score ever equals 21, then play a happy sound/melody and say “WIN”
1.  MAKE IT YOUR OWN: Decide how the player loses. If the player loses, play a sad sound/melody and say “LOSE.” It’s your choice how the player loses. Maybe if the player has pressed the B button too many times? Maybe if the score is ever greater than 42? Maybe if the score is ever less than 1? Maybe if the timer runs out? You might need to add another variable to track something.

When finished, show your game to your teacher. Demonstrate how to win and how to lose.

---

# Variable Flashlight

Make a variable brightness flashlight. Either pushing the buttons or tilting the Micro:bit forward and back should make make the LEDs come on brighter or dimmer. Must have a control to make it brighter and a different control to make it less bright.

---

## Projects with While Loops

---

# Running Game

Imagine that the A and B buttons are actually giant buttons on the floor. The player must alternate between pressing A and then B.

Create a points variable.

Forever...

- While the player hasn't pressed A, display "A"

- While the player has pressed A, display the current points.

- Give the player a point

- While the player hasn't pressed B, display "B"

- While the player has pressed B, display the current points.

- Give the player a point

---

# Reaction Time Game

The project uses while loops and or not

Create a 2-player Reaction Time Game for Microbit. Everyone’s game will be unique.
You will need two variables to store player A’s score and player B’s score.
In the forever loop…

- Show string “3”
- Show string “2”
- Show string “1”
- Show string “”
- while true…
  - pause a random amount (1000 ms equals 1 second)
  - if button A is not pressed and button B is not pressed, then break this while true loop (this code makes sure that no one is pressing a button too early).
- show an icon
- while true…
  - if button A is pressed or button B is pressed, then break this while true loop (this code waits for one of the buttons to be pressed)
- if button A is press, then add points for player A
- do the same for player B if their button is pressed
- show string and join these four things: “A=” + player A’s score + “B=” + player B’s score
- Finally, check to see if the game is over. MAKE IT YOUR OWN: You decide how to win. Maybe if either player is winning by 2 points? Maybe if either player A or player B has 3 points?
- if the game is over, start a while true loop that says either player A wins or player B wins.

When finished, show your game to your teacher. Demonstrate how player A wins and how player B wins.

---

# Bouncing Off The Walls

Create a variable and set it to be a sprite at x 2, y 2

The sprite automatically moves forward and bounces off the walls at random angles.

MAKE IT YOUR OWN: A and B buttons MUST do something, but you get to decide what the A and B buttons do. Ideas:

- A starts/resumes the animation and B pauses the animation
- A increases the speed and B decreases the speed.
- When A and B are pressed at the same time, the sprite moves back to the center.
- A decreases the brightness of the sprite and B increases the brightness.

---

# DDR Game

Create a Dance Dance Revolution game with buttons for the player to press Left = Button A, Right = Button B, Down = Pin 2.

Randomly display Left, Right, or Down. 

Wait until the player presses that button, then randomly display another.

If the player waits too long, then say game over and display the score.

---

# Gyroscope Game

- Create a player sprite
- Change the players x and y location based on the pitch and roll of the microbit
- Divide the pitch by 60 and roll by 60 to decrease the sensitivity
- Use a brief pause (from the Basic section) to control the pause's speed

Once you have the basic player controls.....

- Create an enemy sprite
- Set the enemy sprite's "blink" setting to 100
- Create a SECOND forever loop
- If enemy touches player then game over
- Either move the enemy randomly or have them move towards the player
- Use a pause (from the Basic section) to control the enemy's speed.

---

## Projects with Servo Motors

---

# Robot Arm

Control a standard 9-gram servo with the A and B buttons.

---

# Droid

Combine the light sensor face, create a song, and servo arm projects to create a droid that "talks" and moves it's arms when the light level changes.

---

# RC Car

Connect your microbit to 2 continuous rotation servos.

Use bluetooth to control the microbit's servos from iPad, iPhone, etc.

---

## Projects in MicroPython

---

# MicroPython Speak

Add a speaker. Use the MicroPython editor.

Make your Microbit speak.

http://microbit-micropython.readthedocs.io/en/latest/tutorials/speech.html#say-something (ignore the diagram that shows the wrong way to connect a speaker) Note: You can't just turn in one of the examples from that site.

---

# MicroPython Sing

Attach a speaker. Use the MicroPython code editor.

Make your MicroBit sing.

http://microbit-micropython.readthedocs.io/en/latest/tutorials/speech.html#sing-a-song-of-micro-bit Note: You can't turn in an example from that website.

---

# MicroPython Neopixels

Use the MicroPython editor.

Connect a NeoPixel.

Each time you press the A button, the NeoPixel switches to a random color.

http://microbit-micropython.readthedocs.io/en/latest/neopixel.html

---
