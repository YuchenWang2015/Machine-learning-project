This repository includes all the raw data and scripts we use for training the Machine-learning force fields for the gold thiolate-protected gold nanocluster.

1. In the training direcotry:
all_dft.xyz contains all the coordinates and the corresponded energy information for the structures in the training sets. 

2. In the validation directory:
*coord sub direcotry contains all the optimized structure of gold clusters, those optimized structures have been applied as the starting structure of the molecular dynamics simulations.
*md-frame sub direcotry contains all the structures that we extracted from MD-trajectory and then validated their energy between machine learning and DFT calculations.
*energy sub diretory contains the spreadsheet which compares the energy differences between VASP DFT calculations and machine learning results.




