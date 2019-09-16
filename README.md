# MatchPuzzle

This project addresses efficient manipulation of data structures and pattern matching. The task is a classic IQ test where one is asked to match an eight color pattern to a copy that may be flipped (mirrored) and rotated. The reference puzzle is the square in the center of the board. The eight candidate puzzles wrap around the edge of the board clockwise beginning in the upper left hand corner. The color codes are as follows (0 = red, 1 = yellow, 2 = green, and 3 = blue). The reference pattern in the example below (the center 3 x 3 pattern) is yellow, blue, red, yellow, blue, red, yellow, red. The matched candidate is the pattern mark with an “X” to the left of the reference (pattern 7). Note that it is flipped and rotated. Exactly one of the eight candidates will match the reference pattern; it may be flipped (horizontally or vertically), rotated, or both. The reference and candidate color codes are each packed into the lower 16-bits of an unsigned integer (2 bits per element). The Reference and Candidates arrays shown below show the 2 bit values of each element, and the table shows the values of the corresponding packed unsigned int.
