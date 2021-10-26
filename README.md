# microbit projects

A list of open-ended MicroBit projects


### Functions


### For Loops


### Variables

  - [Clicker Game](#clicker-game)

### While Loops

  - [Reaction Time Game](#reaction-time-game)



## Projects with Functions

## Projects with For Loops

## Projects with Variables

# Clicker Game

Create a timer variable and set it to 5 (or 9).

Create a score variable (or two) and set it to 0.

Countdown from 5 to 0, displaying the timer on the "screen"

When button A is pressed player A gets points. When button B is pressed player B gets points. MAKE IT YOUR OWN: Increase the amount of points over time. Maybe each click doubles your score? Maybe the timer changes your score so that clicks when the timer begins are worth less points and and clicks when the timer is low are worth more points? Maybe the losing player earns a bonus point for each click?

When the timer is zero or less, say who wins... either player A or player B.

## Projects with While Loops

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
