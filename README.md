# AFE-BiFeO3-films   
This repository contains the data supporting our paper *“Antiferroelectricity in BiFeO₃ Thin Films”* (DOI: https://doi.org/10.1103/fqpx-dpbn). The dataset includes calculated order parameters and energies obtained under various conditions using the effective Hamiltonian method. These data were used to generate the figures presented in the main manuscript and the supplemental material.

### Energy (Fig. 2)
The *R3c* and *Pnma* phases correspond to the *R*-like and *O*-like structures in BiFeO3 film, respectively, as described in the paper. 
- first column -- film thickness (number of unit cells)
- second column -- energy (Hartree)

### P-E_loop-data (Fig. 3 & Fig. S10)
filename: a_b_c_pz.dat  
- a -- temperature (K) 
- b -- beta (screening factor)
- c -- film thickness (number of unit cells)
  
### Pnma_Edown (Fig. S9)
filename: a_b_c_pz.dat
- a -- beta (screening factor)
- b -- temperature (K)
- c -- film thickness (number of unit cells)

### heating (Fig. 4 & Fig. S11-13)
filename: Pnma_heating_x_y.dat 
- x -- biaxial strain
- y -- order parameters (polarizations & octahedral rotation angles)
  
### layer_by_layer (Fig. S2)
- uxyz.dat -- components of local modes
- wxyz.dat -- components of octahedral rotation angles

### order_parameters_vs_thickness (Fig. 1 & Fig. S4)
The *R3c*, *Pnma*, and *P4mm* phases correspond to the *R*-like, *O*-like, and *T*-like structures in BiFeO3 film, respectively.  
- p -- polarization (μC/cm²)  
- u -- local mode amplitude  
- w -- octahedral rotation angles (rads)
