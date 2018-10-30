# Baum-Sweet-Sequence
Beginner challenge project for Python

# Mission
The goal of this project was to write a program that generates the Baum-Sweet Sequence from 0 to some user-defined number n.

# Background
Here's some background into the Baum-Sweet sequence, taken from Wikipedia:

In mathematics the Baum–Sweet sequence is an infinite automatic sequence of 0s and 1s defined by the rule:

b_n = 1 if the binary representation of n contains no block of consecutive 0s of odd length;
b_n = 0 otherwise;
for n ≥ 0.

For example, b_4 = 1 because the binary representation of 4 is 100, which only contains one block of consecutive 0s of length 2; whereas b_5 = 0 because the binary representation of 5 is 101, which contains a block of consecutive 0s of length 1.

Starting at n = 0, the first few terms of the Baum–Sweet sequence are:

1, 1, 0, 1, 1, 0, 0, 1, 0, 1, 0, 0, 1, 0, 0, 1 ... (sequence A086747 in the OEIS)
The properties of the sequence were first studied by L.E. Baum and M.M. Sweet in 1976.

