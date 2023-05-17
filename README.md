# trick_pi_collisions
Uses NASA Trick software to simulate collisions described by https://youtu.be/HEfHFsfGXjs

The basic idea is that there are two blocks and a wall. The wall is to the left of both blocks.
At the start of the simulation, the right block (block 2) is sent towards the left block (block 1) with a constant velocity.
After a series of perfectly elastic collisions, the total number of collisions can be used to approximate
pi, given that the mass ratio of the blocks fulfills certain conditions.

This simulation prints all collision times and returns the total collision count at the end.

## Purpose
This is a very simple use of NASA Trick intended to help me learn how to use the software.
