# Knight's Tour

## What is this?

A knight's tour is a sequence of moves of a knight on a chessboard such that it visits every square exactly once.

This project lets you select how big the chessboard is and tries to find a knight's tour solution in it.

## Demo URL

[http://knights-tour.marcosgimeno.com](http://knights-tour.marcosgimeno.com)

## Algorithms

2 different algorithms have been implemented. Both use backtracking. 

1.- Fixed set of moves
The knight always tries to move in the same order. 

2.- Warnsdorff's rule
The knight is moved so that it always proceeds to the square from which the knight will have the fewest onward moves. 
When calculating the number of onward moves for each candidate square, we do not count moves that revisit any square already visited.

Warnsdorff's rule is far more efficient.

## Speed and maximum capacity

The calculations run on your own browser (javascript). 

This means that depending on your browser you might get a "Maximum capacity exceeded" error when trying to solve a very big chessboard.  (This comes from the javascript error "Maximum call stack size exceeded")

Obviously, this also means the faster your device, the faster the calculations.

## Development

This project has been developed in a single file (aside from images) using just plain Javascript, CSS and HTML with no libraries/dependencies.
