# Senior_Honors_Thesis
Code for my senior honors thesis in cognitive science: a Continuous Attractor Network (CAN) model of grid cells that incorporates place cell input

# Overview
All trajectory files from the Hasselmo lab are included in this repository (though I only use 3 different trajectory datasets
for the actual project). get_trajectory.py and quad_flip.py were auxiliary scripts written by Ron DiTullio for easier
implementation.

place_cell.py and place_cell_utilities.py create a population of place cells used in the CAN grid cell model.

EP_XW_RD_RWD_ZPS_main.py and EP_XW_RD_RWD_ZPS_experiment.py are the main files that implement the CAN model. The former was used to train the model and obtain the place cell sub-populations and place-grid weights. The latter runs the cognitive map 
switching experiment with new trajectory data with the place cells and weights from training.
