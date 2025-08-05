# Intro
We try to implement a custom w_de in class

# Steps
1. at input_init.c we make changes so to allow for different w_de model in the same lines with "CLP"
2. At background.h we add within background struct any extra free parameters
3. We provide at background.c all needed functions of the effective fluid approach, i.e. w_d, d_wde/da etc.

# status and ideas
1. The H(a=1) is half of the input H_0 -- contradiction
2. the w_de has oscillations at small a, i.e. a \sim 0.001
3. large variability of the results as a function of the parameter "a_ini_over_a_today_default"
4. the problem could be related with the fact that w_{DE} = 0 at early times breaks stuff within class
as discussed at https://github.com/lesgourg/class_public/issues/425
5. 