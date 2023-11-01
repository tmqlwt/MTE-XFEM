# MTE-XFEM
##Paper titile
A new Minimum Total Energy Extended Finite Element Method (MTE-XFEM) to simulate the initiation and development of multiple cracks
##main_program
### Description
This paper presents the Minimum Total Energy Extended Finite Element Method (MTE-XFEM) to address the initiation and development problems of multiple cracks, which can be applied to the fracture analysis of linear elastic plane members under quasi-static and small deformation conditions. The proposed crack competition criterion is based on the minimum total energy principle. The initiation or propagation of cracks per unit length would lead to the maximum energy dissipation. Besides, a novel adaptive contact stiffness algorithm is proposed to tackle multi-crack contact surface simulation. The application of adaptive contact stiffness improves the convergence and applicability of contact simulations. The MTE-XFEM is realized by the MATLAB programming.
##
"RUN.m" is the file to initiate the calculation. You need to input the folder name and its corresponding path in sequence where the calculation file"JOB_MAIN.m" is located.
"JOB_MAIN.m"  contains the configuration details for the numerical model.
##Author
Tao Wang
School of Civil Engineering, Central South University, Changsha 410075, China
##

ACKNOWLEDGEMENT
This program was enhanced based on the open-source code provided by Danas Sutula. Therefore, we would like to express our gratitude to Danas Sutula for their assistance in this research.

Danas Sutula, University of Luxembourg, Luxembourg.
* [Minimum energy multiple crack propagation](http://hdl.handle.net/10993/29414)
