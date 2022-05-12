# Collinear Points

Recognizing patters in data is an important problem in computer science, especially
in computer vision which powers everything from your phone's facial recognition
and fingerprint scanner to self-driving cars and airplane guidance systems. In this
lab, you will attempt to solve a problem closely reltated to computer vision: identifying
collinear points.

## Lines in the plane
We say that a group of points are _colinear_ if there is a single straight line that
passes through all of them. For this project, you will be given a random set of (x,y) points
in the plane. Your task is to identify all of the sets of points which are collinear.


### The problem
Given a set of _n_ points in the x-y plane, find every maximal set of four or more collinear points.
Note, by _maximal_ we mean "biggest." So if a line goes through six points, we want to know about
all six, not just _some_ of them.

![Example](https://coursera.cs.princeton.edu/algs4/assignments/collinear/lines2.png)

