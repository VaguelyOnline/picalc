# picalc
Simple HTML example of how to calculate PI from random estimates.

## How does it work?
The code uses the HTML Canvas API to draw a circle, bounded by a square. It then proceeds to add a random dot to the picture, until the desired total of dots is reached?

## How does this calculate PI?
One of the ways to calculate PI, is to look at the ratio of the area of a circle, to the area of a square it's in. Consider a circle of radius 1:

- The area of the circle will be given by PI x radius squared.
- The area of the square will be given by 2r x 2r = 4r2.
- If you add enough random dots to the image, the ratio of the dots inside the circle, to the total number of dots, will be a good approximation of the relative areas.
- You can then do a little simple maths to estimate PI


