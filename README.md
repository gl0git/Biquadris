# Biquadris
A multiplayer, terminal-based implementation of Tetris

## Code
The code for this project is available on request, in order to adhere to my university's policy (Policy 71).
While I would like to share this openly, my university does not allow so as it would compromise the integrity
of the course this project was written for (CS246).

## Features
- Block rotations (clockwise, counterclockwise), drops, shifts in any direction 
- Score tracking using a variant of Tetris rules 
- Special actions (blind, heavy, force)
- Five different levels, where each level has increased difficulty and a higher score reward.
- Can play with another person (multiplayer)

## Design
The design for the project is outlined in the UML below. The design is based on OOP rules/patterns. 
The most important components are the use of the Decorator pattern for implementing special effects, 
and the factory method pattern for levels. Different polymorphic approaches were used for other components,
with a goal of achieving minimal re-compilation on modification (and of course high cohesion, low coupling).

<img src='./images/uml.png'> 
