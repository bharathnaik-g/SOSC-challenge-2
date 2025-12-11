In the optimized version, instead of rotating step-by-step, I used modulo rotation.
This means:

I directly calculate how far a row needs to shift.

I then rebuild the rotated row in one step using string slicing.

Because of this:

No repeated loops

Rotation happens in O(n) time instead of O(n × rotations)

Code becomes shorter and cleaner
