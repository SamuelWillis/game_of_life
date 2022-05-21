# GameOfLife
An Elixir implementation of [Conway's Game of
Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life).

## Rules
The game happens on a 2D grid of _cells_.

Each cell can be one of two possible states: _live_ or _dead_ and it interacts
with its eight neighbours.

At each step in time the following transitions occur:

1. Any _live_ cell with less than 2 _live_ neighbours dies, as if by
   underpopulation
1. Any _live_ cell with 2 or 3 _live_ neighbours lives to the next generation
1. Any _live_ cells with more than 3 _live_ neighbours dies, as if by
   overpopulation
1. Any _dead_ cell with exactly 3 _live_ neighbours becomes _live_, as if by
   reproduction

The initial pattern, or state, of the grid is the _seed_ of the system.

## Installation

1. Run `mix deps.get`

## Architecture
TODO: Fill this out to illustrate things.

## Playing a game
TODO: Tell people how they can play this game!
