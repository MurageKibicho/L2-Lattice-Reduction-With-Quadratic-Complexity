# L2 Reduction: LLL Algorithm With Quadratic Complexityv
Coding the 2009 paper that introduced the L2 floating-point reduction algorithm: _An LLL Algorithm With Quadratic Complexity_ (Nguyen & Stehle, 2009). Complete writeup available on [LeetArxiv](https://leetarxiv.substack.com/p/l2-reduction-fast-lll-quadratic-complexity).

![Screenshot of Paper Abstract](Abstract.png)
The _1982 paper, Theorems on Factorization and Primality Testing_ (Pollard, 1974) introduces a special-purpose `p-1` algorithm for factoring integers composite integers `N`, into prime factors `p`, where `(p-1)` has small prime factors.


## Getting Started

The repo is written to be followed alongside this [LeetArxiv article](https://leetarxiv.substack.com/p/pollards-p-1-factoring-algorithm).

Clone the repo and run using:
```
clear && gcc main.c -o m.o -lm -lgmp -lmpfr -lflint && ./m.o 
```



You might also enjoy:
1. [Gauss-Lagrange 2D Lattice Reduction](https://leetarxiv.substack.com/p/2-dimensional-lattice-basis-reduction).
2. [Gauss Lattice Sieving](https://leetarxiv.substack.com/p/gauss-lll-sieve)

