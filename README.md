# exponential-Diophantine-equations
Magma code for finding powers of *p* that can be written as the sum of a small number of distinct powers of *q*, for (*p*,*q*) = (2,3) and (3,2).

This repository contains Magma code related to the paper “Powers of 3 with few nonzero bits and a conjecture of Erdős” by Vassil S. Dimitrov and Everett W. Howe, which will appear in the *Rocky Mountain Journal of Mathematics*.

The paper considers exponential Diophantine equations of the form *q*^*x* = *p*^{*a_1*} + ... + *p*^{*a_n*} for distinct primes *p* and *q* and various values of *n*, with the further restriction that the summands on the right hand side be distinct. This file contains Magma code for the case *p* = 2 and *q* = 3 (so that we are trying to determine which powers of 3 have few nonzero bits when expressed in binary) and on the case *p* = 3 and *q* = 2 (related to a conjecture of Erdős that there are only three solutions to the equation, even if *n* is allowed to vary, corresponding to *x* = 0, *x* = 2, and *x* = 8).

To find the powers of 3 that can be written as the sum of 10 distinct powers of 2, for example, enter:

    P3_as_sum_of_P2(10);

Likewise, to find the powers of 2 that can be written as the sum of 10 distinct powers of 3, enter:

    P2_as_sum_of_P3(10);
  
