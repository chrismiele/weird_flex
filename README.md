# weird_flex

Notebooks applying flexure to the SSA, with functionality from Firedrake and icepack, guided by MacAyeal et al. (2021). 

**Notebook summaries**:

- 0_modified_SSA_firedrake: *modify the SSA, using either Firedrake or icepack, to permit small deviations from isostatic equilibrium*
- 1_kirchhoff_plate_elastic.ipynb: *use firedrake to solve the vertical elastic deflection of a thin plate under a uniform load*
- 2_kirchhoff_plate_viscous.ipynb: *use firedrake to solve the vertical viscous rate of deflection of a thin plate under a uniform load*
- 3_coupled_flow_flexure_elastic.ipynb: *use firedrake and icepack to couple viscous flow with elastic deflection, from notebooks 0 and 1*
- 4_coupled_flow_flexure_viscous.ipnb (forthcoming): *use firedrake and icepack to couple viscous flow with viscous deflection, from 0 and 2*
- fracture_test.ipynb: *copied notebook by [Hirshikesh](https://github.com/Hirshikesh) applying the phase field method to model fracture propagation*
