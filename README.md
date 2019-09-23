# YbErQS
Simulation of Q-switched single-mode dynamics in a short-cavity Yb:Er:glass laser

The code was used for Photonics West 2017 paper 
V.Vitkin, et.al. "Pulse-burst Er:glass laser" https://doi.org/10.1117/12.2252107

The code is written for Wolfram Mathematica, however, one can use the parameters 
and approach for other languages. 

The text file can be opened with Wolfram Mathematica, and then it is better to perform three steps:
1) Select all cells
2) Cell -> Merge Cells
3) Cell -> Convert To -> StandardForm Display

The code performs the integration of the rate equations presented in the aforementioned paper
iterating the values of the pump intensity from near the threshold value to 50% the threshold value.

Currently, 21 steps are performed, and it is small-step BDF algorithm, so it can be rather slow.
