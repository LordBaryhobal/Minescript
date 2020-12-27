# How to read this file:
numbers (1, 2, 3...) -> indicate the layer of the block i.e 1 is the ground layer, 2 is the second block under, 3 the third etc.
letters (a, b, c...) -> indicate multiple possibilities for the same layer.
*TODO* -> to do

# End of program:
    1: obsidian


# Null operation
    1: bedrock


# Values:
    2a: barrel with certain number of item (in 1st slot) -> direct assignation
    2b: coloured wool/concrete -> value from other variable
    2c: air -> internal value
    2d: chiseled stone bricks -> value from internal accumulator


# Variable assignation:
    1a: coloured wool -> local variable
    1b: coloured concrete -> global variable
    2: value (see #Values)


# Print:
    1: redstone lamp
    2: value (see #Values)


# Arithmetic Operators

## Addition:
    1: nether wart block
    2: Value A (see #Values)
    3: Value B (see #Values)

## Subtraction:
    1: warped wart block
    2: Value A (see #Values)
    3: Value B (see #Values)

## Multiplication:
    1: slime block
    2: Value A (see #Values)
    3: Value B (see #Values)
    *TODO*

## Division:
    1: honey block
    2: Value A (see #Values)
    3: Value B (see #Values)
    *TODO*

## Modulo:
    1: honeycomb block
    2: Value A (see #Values)
    3: Value B (see #Values)


# Threading:
    1: bookshelf
    2a: air -> evaluates to true
    2b: condition (see #Values)


# Comparison Operators:
    1a: carved pumpkin -> !=
    1b: packed ice -> <
    1c: blue ice -> >
    2: Value A (see #Values)
    3: Value B (see #Values)


# Logical Operators:

## Not:
    1: sea lantern
    2: value (see #Values)

## Or:
    1: piston
    2: Value A (see #Values)
    3: Value B (see #Values)

## And:
    1: sticky piston
    2: Value A (see #Values)
    3: Value B (see #Values)


# Branch:
    1: magenta glazed terracota
    2a: air -> evaluates to true
    2b: condition (see #Values)


# Function:

## Definition:
    1: stained glass
    2: redstone block

## Usage:
    1: stained glass

## Delete:
    1: stained glass
    2: magma block


# Pause:
    1: target
    2: condition (see #Values)
