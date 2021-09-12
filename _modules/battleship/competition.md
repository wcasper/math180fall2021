---
layout: page
title: Battleship Commander Competition
permalink: /modules/battleship/competition
---

<p align="center"><img src="fig/captainpic.jpg" width="50%"/></p>

## Do **you** have what it takes to be the Ultimate Battleship Commander?
In this assignment, you and your group will compete against the other groups for **glory**, for **fame**, and for **incredible prizes**!

Your objective is to describe a strategy for choosing where to fire shots in order to sink an enemy fleet.  Your intrepid professor Riley will program your strategy you describe into a computer, and then test it against ten thousand different randomly positioned enemy fleets!  Using this, Riley will compute on average how many shots it takes to sink a fleet.  The winning team will be the one with the lowest average number of shots.  The members of the winning group will reap the following rewards

* the members proclaimed on the Canvas homepage
* their strategy will be posted publicly
* the members get real-world fantastic and amazing prizes (announced after).

That's right folks.  It could be **food**.  It could be **swag**.  It could be **yours**.

Instructions
Your group must agree on what you think will be the best strategy for sinking a standard fleet in Battleship in as few shots as possible.  You must then describe your strategy in a single page, typed up.  Only **one submission per group** is allowed.  Your strategy can be super elaborate, but you have to be able to describe it in a very clear and detailed way on a **single page**.  If what you want done is not clear from how it is written, the submission will need to be revised by the group.  Part of the idea of the exercise is thinking about how to be precise with language.  Communicating technical information to other people in a clear way is a key part of math!  Some examples of possible submissions are given below.  (Hopefully your strategy is more clever though!)

Submission deadline: midnight on September 11th
Submissions are mandatory and will be graded.

### Example Strategy 1

Shoot first at all of the locations on the edge, starting from the upper left corner and proceeding clockwise.
Once all of those spaces are done, use a random number generator to choose a space to fire at that is different from the previous spaces.
If the number of 
Shoot first at the square A1.  At any point, to pick the next shot, just go to the right of the previous shot.  For example, if the last shot was B3, then the next shot will be B4.  If you can't go to the right, then instead make the next shot at the beginning of the next row.  For example, if the last shot was C10, then the next shot will be D10. 

### Example Strategy 2
Choose the first shot randomly anywhere in the grid.  At any point, if the previous shot is a miss, then to pick the next shot simply randomly choose a square where you have not fired before.  However, if the previous shot was a hit then follow this protocol:

if the last shot was the first shot on a new ship, then shoot next randomly at adjacent squares until you get a second hit.
if the last shot was not the first shot on a ship, guess randomly one of the two adjacent squares in line with the previous two shots.  Continuing this part will eventually fill out and sink the ship
if the last shot sank a ship, just randomly guess a square where you have not fired before.
