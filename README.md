System Level Model of micromirror cell in VHDL-AMS generated by ANSYS ROM Tool
==============================================================================

![micromirror](https://user-images.githubusercontent.com/5137813/132745360-81275711-359b-4739-8dd0-8121eef9f312.png)

The goal of this project is to popularize of Mode Superposition based Reduced Order Modeling technique for MEMS simulations.

Tutorial:
Kolchuzhin, Vladimir and Mehner, Jan (2015, June 30). System level modeling of the micromirror cell. Zenodo. 10.5281/zenodo.19153

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19153.svg)](https://doi.org/10.5281/zenodo.19153)

Simplorer model:
----------------

coming soon ...

Simulink Model:
---------------

  Simulink model of the micromirror cell:
   * micromirror_ini.m
   * sene.m
   * cap12.m
   * cap13.m
   * cap23.m
   * micromirror.mdl

Geometric model:
----------------

  The CAD geometry of the micromiror cell in an IGES format.

hAMSter model:
--------------

  variant 1: "Original Model" with comments + testbench.vhd;
  
  variant 2: micromirror.vhd (single file w/o packages);
  
  variant 3: micromirror.vhd (w/o SIGNAL) in progress;
  
  The vhd-files have been compiled with hAMSter simulator.

Original Model:
---------------

  Original Model of micromirror cell generated by ANSYS ROM Tool:
   * initial.vhd
   * ca12_ams_130.vhd
   * ca13_ams_130.vhd
   * ca23_ams_130.vhd
   * s_ams_130.vhd
   * transducer.vhd
