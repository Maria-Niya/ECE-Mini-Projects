The Problem statement is given like this :
You are given a Differential equation: y'''(t) + 7y''(t) + 10y'(t) = Ku(t)
where y(t) is output and u(t) is input.

Design the system by selecting an appropriate gain K such that
1) peak overshoot will be less than or equal to 20%.
2) Settling time is less than or equal to 2sec.
3) System bust be stable and reasonably robust.

SOLUTION:
1) Convert the differential equation into a transfer function:
   y(s)/u(s) = K / s^3 + 7s^2 + s^10
2)Find the system order and the poles of the open loop transfer function
3)Sketch the root locus
4) Determine the range of K for stability.
5) Compute the damping ratio and estimate the pole location
6) Determine stable values of K.
7) Using Nyquist Stability criteria find the gain and phase margin
8) Use Matlab

But by doing this you will realize that the system doesen't satisfy the conditions hence we add a lead compensator to get the right values.
