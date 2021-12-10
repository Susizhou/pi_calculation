# Calculating π

The code in this repository estimates the value of π by a
Monte Carlo process described below.

We will use it as an example to measure, and later improve,
the performance of Python code. 

## How to run

You can run the code with `python calc_pi.py`.
There are some options you can customise. See the help message
(`python calc_pi.py --help`) or the look at [the code](calc_pi.py)
to see what those are.

## How it works

In this approach, π is approximated by
- sampling n random points inside a square with side length 1,
- counting the number of those points that fall inside a circle,
- and multiplying that by 4/n
 
