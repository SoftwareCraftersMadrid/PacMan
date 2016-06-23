# Kata - Coding Dojo

## Objectives
> The focus is to practice writing the best code we can possibly write and challenge ourselves. It is important to mention that the goal is not to finish the exercise as soon as possible, but to learn during the process via the discussion with our partner.

## Requirements
> Each developer must come with their favourite IDE ready to start practicing TDD, ideally with an empty class or function and its associated test prepared to be launched.

## Rules
* Developers should work in pairs.
* As a rule, Test-Driven Development is mandatory. If you are unaware of this procedure, please try to pair with someone who does.
* We will run a small retrospective at the end of the session where we will discuss what difficulties we found, what we have done and what we have learnt.
* Developers would thank their pairs when the session is over.

## What you should NOT expect from this dojo session
* It's neither a master class nor a workshop, but you will learn new approaches to face problems from different perspectives.  
* It's not a place to learn new languages. At least, one of the pair should be comfortable with the chosen programming language.
* It's not a place to learn how to set up an environment.

## How to start
1. **Find a pair**.
2. **Decide** which **programming language** you are going to use and in which laptop you will code.
3. **Read carefully the problem** described below and if you have any doubt, please refer to the facilitator.

***

## PacMan

## Before you start:
* Do one task at a time. The trick is to learn to work incrementally.

### PacMan

Pacman finds himself in a grid filled with monsters. Will he be able to eat all the dots on the board before the monsters eat him?

Incomplete list of things the game needs:

 * pacman is on a grid filled with dots
 * pacman has a direction
 * pacman moves on each tick
 * user can rotate pacman
 * pacman eats dots
 * pacman wraps around 
 * pacman stops on wall
 * pacman will not rotate into a wall
 * game score (levels completed, number of dots eaten in this level)
 * monsters...
 * levels
 * animate pacman eating (mouth opens and closes)

##### Clues

You probably won't be able to complete all of the list in one night of dojo, however having the list (or starting with part of it and letting the participants brainstorm) makes for good design discussions. As in the game of life, a board representation does not have to be difficult. E.g. pacman starts in the centre of the board and is looking up (notice that pacman eats, so the V points downward because pacman has his mouth open):

. . .
.V. 
. . .

Pacman looks continuous, however the game state changes in discrete steps. Creating a tick() method/function or somesuch, or passing a board to a function which returns a 'next state' board makes it easy to test the various conditions.

Web: http://codingdojo.org/cgi-bin/index.pl?KataPacMan
