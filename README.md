# Phyllotaxis
R DS Project -6. \n
There are many examples of natural facts that can be described in mathematical terms. Nice examples are the shape of snowflakes, the fractal geometry of 
romanesco broccoli or how self-similarity rules the growth of plants.
Let's start by loading the library.

We'll start by drawing 50 points on a circle of radius 1. As every (x, y) point should be in the unit circle, it follows that x² + y² = 1. We can get this 
using the super famous Pythagorean trigonometric identity which states that sin²(θ) + cos²(θ) = 1 for any real number θ.

The Golden Angle is the angle subtended by the smaller (red) arc. Both the Golden Ratio and the Golden Angle appear in unexpected places in nature. Apart 
of flower petals and plant leaves, you'll find them in seed heads, pine cones, sunflower seeds, shells, spiral galaxies, hurricanes, etc.

It's time to spiralize!

Apart from data, a plot includes many other components that define its final appearance. Our previous plot contains:

- a background filled with grey color
- a grid of horizontal and vertical white lines
- ticks along the axis
- a title on each axis
- text along axes to label marks
Art does not get along with most of these elements, so it's time to move to action.

Our drawing is starting to look like a plant, but we can better. By changing color, transparency (also called alpha), and size of the points, the image will 
become more appealing.

Until now, all points have the same appearance (size, color, shape, and alpha). Sometimes we will want to make the appearance of the points dependent on a 
variable in the dataset. Now we will make the size variable. We will also change the shape of the points. Although we won't be able to blow on it, the resulting 
image should remind you of a dandelion.

Plants not only use the Golden Angle to arrange leaves. The Golden Angle is also found in the arrangement of sunflower seeds. We don't need anything new to draw 
a sunflower; we just need to combine some of the things we already know.

These patterns are very sensitive to the angle between the points that form the spiral. Small changes to the angle can generate very different images. Let's look 
at an example of that.

All together now: imaginary flowers
