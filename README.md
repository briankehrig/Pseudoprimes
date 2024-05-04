# Pseudoprimes
Lists of pseudoprimes above 2^64

# Background
Craig Loizides tested all prime gaps from 2^64 to 2^64+2^60 using only a single Fermat test to base 2, after sieving with primes up to 39000.
This means that he may have missed a small subset of numbers - namely, ones that are weak Fermat pseudoprimes to base 2, and have no prime factors below 39000.

Currently, there is 1 list in this repository: located at "lists/pseudoprimes_2_64_gap1572_rough39000.txt"

This file contains a list of every base-2 pseudoprime from 2^64 to X = 18571673432051830099 that has no prime factors below 39000.
X is the starting point of a prime gap of length 1572, which is the 82nd maximal gap.
This is the complete list of pseudoprimes that Craig's code missed. The largest prime gap containing a pseudoprime in this list is just 684, which surrounds the pseudoprime 18520296964033962991.
With these two pieces together, Craig's work with prime gaps and my work with pseudoprimes, we have now verified the 1572 gap.
