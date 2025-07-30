# Intro
We try to implement a custom w_de in class

# Steps
1. at input_init.c we make changes so to allow for different w_de model in the same lines with "CLP"
2. At background.h we add witkin background struct any extra free parameters
3. We provide at background.c all needed functions of the effective fluid approach, i.e. w_d, d_wde/da etc.
4. We enhance 'background_w_fld' to contain also a pointer to the modified c_s,de^2.


