This repository includes all the raw data and scripts we use for training the Machine-learning force fields for the gold thiolate-protected gold nanocluster.

1. In the training direcotry:
all_dft.xyz contains all the coordinates and the corresponded energy information for the structures in the training sets. 

2. In the validation directory:
*coord sub direcotry contains all the optimized structure of gold clusters, those optimized structures have been applied as the starting structure of the molecular dynamics simulations.
*energy sub diretory contains the spreadsheet which compare the energy differences between vasp DFT calculations and machine learning results.




