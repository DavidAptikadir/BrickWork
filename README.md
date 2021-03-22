# BrickWork

console app that accepts input parameters for a given layout of bricks, then determines whether it is possible to build another layer.

The builders must cover a rectangular area of size M × N (M and N are even numbers)
with two layers of bricks that are rectangles of size 1 × 2. The first layer of the bricks has
already been completed. The second layer (in an effort to make the brickwork really
strong) must be created in a way that no brick in it lies exactly on a brick from the first
layer. However, it is allowed half of the same brick to lie on the same brick on the second
layer.



Input
1. N, M — dimensions of the area (both layers’ dimension a.k.a wall thickness/width
and length).
NOTE: Each brick is marked with two equal numbers written in the squares of the
area that are covered by this brick. All bricks are marked with whole numbers
ranging from 1 to the total number of the bricks. M and N are even numbers not
exceeding 100.
Output
Write N lines with M numbers each that describe the layout of the second layer in the way
shown above
