# Solar-Oven-Model
This program is useful for modelling the reflection of light rays off of the side panels of a solar oven.

As a general model for the oven, we assume there is a square window of side length l at the bottom, and there are four reflectors total.
Each reflector is a trapezoid, with the smaller base equal to l, the length of the reflector equal to m, and the larger base equal to A, which is a precalculated value.

With this model, in seeing the overall reflection map, the true value that affects the final map is m / l, so setting l to 1.0 and m to some value will cover all possible maps.
