[![](https://img.shields.io/badge/arXiv-2303.07426%20-red.svg)](https://arxiv.org/abs/2303.07426)

# Modification of CLASS (v3.1.1) for Decaying dark matter into photons

This modified version of the [CLASS](https://github.com/lesgourg/class_public) code allows to take into account energy injection from DM, in the form of ALP decaying into photons, taking into account energy deposition efficiencies computed with DarkHistory and tabulated at for z=300.  For specific reionization histories (Puchwein or Fauchere-Giguere) different from tanh contact the author.

This code can be used freely provided you cite the specific release paper ([Capozzi, Ferreira, Lopez-Honorez, Mena '23](https://arxiv.org/abs/2303.07426)) and the original CLASS release paper ([Blas et al. 2011](https://arxiv.org/abs/1104.2933)).


The code has been edited by L. Lopez-Honorez (llopezho AT ulb.be). We refer to the main CLASS code [wiki](https://github.com/lesgourg/class_public/wiki/Installation) for installations instructions. The main modifications with respect to the original version are in input.c and .h, thermodynamics.c and .h, injection.c and .h,  and precision.h and the tabulated values of energy deposition efficiencies in terms of ALP mass and coupling are in external/heating/axion_f300_gridforCLASS.dat. An input file axion-params.ini has been created with the basic quantities needed in order to run the modified code.

