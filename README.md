# pi-darts
Estimating pi using a Monte Carlo simulation!

Goal of this project:
To to do this, imagine a circular dart board of radius 0.5 units pinned to a square wall, and randomly throw darts at the wall. Take note of where the darts hit the wall and whether or not they fall within our outwith the dart board (assuming the dart must hit somewhere within that square wall).

# Part 1: Obtaining the data
 - Construct a function darts(n) that will simulate the dart throwing experiment and return an nx2 numpy array of both the sample of points and whether they are inside the circle (1) or outside the circle (0).

- Then for n = [50,100,1000,10000], simulate points within the unit square and determine whether or not these fall inside the circle.

- Determine mathematically how to use the proportion of points that fall inside the circle to estimate pi. Using these simulated points, calculate an estimate of pi for each n and store these in a dictionary with the keys being the size of n and the values of the estimate of pi.

  # Part 2: Presenting the results
- Produce a single plot made up of four subplots, with each showing the dart throws for varying n. Ensure that there is a visual distinction between the points falling inside the circle and those falling outwith it and print the estimate of pi and the corresponding n in the title of each subplot.

- Using darts(n), calculate an estimate of pi for a range of n from 100 to 10000 by 100 and plot a scatterplot of the results against n.
