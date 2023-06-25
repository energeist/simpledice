# Simpledice module
A simple module to simulate customizable dice rolls and coin flips.  This module will roll any combination of dice with 4, 6, 8, 10, 12, 20 or 100 sides. 

## Installation instructions
Install this module into your project with `npm install simpledice`

## Methods // Usage
- `.coinFlip()` takes no arguments and will randomly return 'heads' or 'tails' as a string.
- `.rollOne()` takes one argument (sides) which must be an integer.  If not in the list of available dice (4, 6, 8, 10, 12, 20 or 100) then it will return an error message, otherwise it will return randomly rolled die of the given number of sides.
- `.rollMany()` takes one argument (dice), which must be a single die group as a string or many die groups as an array of strings.  Strings must be of format `"<NUMBER>d<SIDES>"`, e.g. `"2d6"` or `"3d20"` for a group of one die type, or `["2d6", "1d20"]` for a group of many dice types, where `<NUMBER>` is the number of dice in a group of dice with `<SIDES>` number of sides.

![package version](https://img.shields.io/npm/v/simpledice)
![total downloads](https://img.shields.io/npm/dt/simpledice)