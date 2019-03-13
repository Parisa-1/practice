# practice
transition-density-calculation : I add subroutine 'plot_cube_transition_density'to the src for calculating transition density. For this perpose we made few changes in this order:
1) File 'io.f90' in src folder which is includes subroutine 'plot_cube_transition_density'.
2) File 'linear_response.f90' in src folder which calls this subroutine.
3) Script 'input_variables.py' in utils folder and adding a new input variable key by name 'print_trans_density_matrix' (don't forget to run this script to makes some changes in src folder).
4) Adding mentioned key to module 'm_inputparam.f90' in src folder.
transition-density-calculation : subroutine 'plot_cube_transition_density' with key in input variable 'print_trans_density_matrix' is added to file 'io.f90' for calculating both transition density and transition density matrix. Attention: This branch still is in examining level.
