# microbit projects

A list of open-ended MicroBit projects


[Functions](#projects-with-functions)


[For Loops](#projects-with-for-loops)

  - [Get Loopy](#get-loopy)


[Variables](#projects-with-variables)

  - [Clicker Game](#clicker-game)
  - [Weird Blackjack](#weird-blackjack)

[While Loops](#projects-with-while-loops)

  - [Reaction Time Game](#reaction-time-game)



## Projects with Functions

---

## Projects with For Loops

---

# Get Loopy

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

## Projects with Variables

---

# Clicker Game

Player A will be clicking the A button as quickly as possible. Player B will be clicking B button as quickly as possible. Highest score wins.

1.  Create a timer variable and set it to 5 (or 9).

1.  Create a score variable (or two) and set it to 0.

1.  Countdown from 5 to 0, displaying the timer on the "screen"

1.  When button A is pressed player A gets points. When button B is pressed player B gets points. MAKE IT YOUR OWN: Increase the amount of points over time. Maybe each click doubles your score? Maybe the timer changes your score so that clicks when the timer begins are worth less points and and clicks when the timer is low are worth more points? Maybe the losing player earns a bonus point for each click?

1.  When the timer is zero or less, say who wins... either player A or player B.

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

## Projects with While Loops

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
