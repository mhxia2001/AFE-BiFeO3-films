# AFE-BiFeO3-films
This repository provides the dataset supporting the figures presented in the paper *“Antiferroelectricity in BiFeO₃ Thin Films”*. The data include calculated energies, polarizations, and order parameters associated with the structures discussed in the manuscript and supplementary material.

## Dataset for the paper *“Antiferroelectricity in BiFeO₃ Thin Films”*

### Energy
The *R3c* and *Pnma* phases correspond to the *R*-like and *O*-like structures, respectively, as defined in the paper. 
- first column -- the number of film layers (equivalently representing the film thickness)
- second column -- the energy values (Hartree)

### P-E_loop-data
filename: a_b_c_pz.dat  
- a -- temperature (K) 
- b -- beta  
- c -- the number of film layers
  
### Pnma_Edown
filename: a_b_c_pz.dat
- a -- beta
- b -- temperature (K)
- c -- number of film layers

### heating
filename: Pnma_heating_x_y.dat 
- x -- biaxial strain
- y -- order parameters (polarizations & octahedral rotation angles)
  
### layer_by_layer
- uxyz.dat -- components of local modes
- wxyz.dat -- components of octahedral rotation angles

### order_parameters_vs_thickness
The *R3c*, *Pnma*, and *P4mm* phases correspond to the *R*-like, *O*-like, and *T*-like structures, respectively.  
- p -- polarization (μC/cm²)  
- u -- local mode amplitude  
- w -- octahedral rotation angles (rads)
