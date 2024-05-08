# BowlingGame 

## Description

Welcome to Bowling Game kata! This isn't just any game - it's a deep dive into the world of Test-Driven Development (TDD). Developed as a "kata", this project showcases the power of writing tests before code. 
It stands as a testament to how this approach can lead to robust, reliable software. So, why not dive in? Explore the intricacies of this methodology, one test case at a time!

## Bowling rules

The game consists of 10 frames. In each frame the player has two rolls to knock down 10 pins. The score for the frame is the total number of pins knocked down, plus bonuses for strikes and spares.

A spare is when the player knocks down all 10 pins in two rolls. The bonus for that frame is the number of pins knocked down by the next roll.

A strike is when the player knocks down all 10 pins on his first roll. The frame is then completed with a single roll. The bonus for that frame is the value of the next two rolls.

In the tenth frame a player who rolls a spare or strike is allowed to roll the extra balls to complete the frame. However no more than three balls can be rolled in tenth frame.

## Requirements

Write a class Game that has two methods:

1. `void roll(int)` is called each time the player rolls a ball. The argument is the number of pins knocked down.
2. `int score()` returns the total score for that game.

