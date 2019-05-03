Add your answers to the Algorithms exercises here.

1a: o(n^3)
1b: o(n^3)
1c: o(n)

2. In general, my approach would mimic a binary sort algorithm. I would begin in the middle floor (n/2, rounded down) and drop an egg. If the egg breaks, I would eliminate the top half of the building and travel halfway down the remaining possible floors (to 25% off the ground, in this case.) If the egg didn't break at the new test floor, I would eliminate the floors below that point and travel halfway up the remaining possible floors.

After repeating this process, we will be left with two floors. If the egg is safe on the top floor, then it is our break point. Otherwise, the bottom floor is our break point.

This function is O(logN)
