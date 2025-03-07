

IRC using [Gaussian](www.gaussian.com/irc) has three converging parameters:    
StepSize=N : Step size along the reaction path, in units of 0.01 Bohr. If N<0, then the step size is taken in units of 0.01 amu1/2-Bohr. The default is 10.
Maxpoints=N : Number of points along the reaction path to examine (in each direction if both are being considered). The default is 10.   
Phase=(N1, N2 [,N3 [,N4]]) : Defines the phase for the transition vector such that forward motion along the transition vector corresponds to an increase in the specified internal coordinate, designated by up to four atom numbers. If two atom numbers are given, the coordinate is a bond stretch between the two atoms; three atom numbers specify an angle bend; and four atoms define a dihedral angle.

Instructions on checking if the initial structure is the maxima energy structure (i.e., transition state) using GaussView can be found [here](https://flex.phys.tohoku.ac.jp/texi/gview/seqs.htm).
[1] [Research Gate: How to get IRC path in Gaussian](https://www.researchgate.net/post/How-to-get-the-IRC-path-in-DFT-Gaussian-calculation)
