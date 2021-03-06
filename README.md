# Exponential-HMC

Hello, this is the implementation of exponential HMC.

Please refer to the ICML 2015 paper for more details:
Wei-Lun Chao, Justin Solomon, Dominik Michels, and Fei Sha, "Exponential Integration for Hamiltonian Monte Carlo," ICML 2015.

The codes are not fully ready yet. If you have any problem with them, please email weilunc@usc.edu, thanks.
Please also see the followings for information about other packages to download.

Please download "liblinear" 1.96 and put it into the BLR folder, for efficiently computing the mode for Laplace approximation.
http://www.csie.ntu.edu.tw/~cjlin/liblinear/

To compare with Riemannian Manifold HMC and Lagrangian HMC, please download the codes from the authors at:
- RHMHC: http://www.dcs.gla.ac.uk/inference/rmhmc/
- LMC: http://www.ics.uci.edu/~babaks/Site/Codes.html
- ** The package of RMHMC also contains the evaluation codes (i.e., for computing the effective sample size) **

# Updated History:
- 5/18/2015: Codes for BLR are ready
- 8/15/2015: Data for MNIST/ICA are ready; The codes will be ready soon
- 8/26/2015: new package is uploaded. BLR/BLR_MNIST/ICA are ready, thanks
