This repository includes all the raw data and scripts we use for training the Machine-learning force fields for the gold thiolate-protected gold nanocluster.
The study associated with this repository has been published in Journal of Chemical Information and Modeling https://pubs.acs.org/doi/10.1021/acs.jcim.4c01495, titled Gaussian Process Approach to Constructing Transferable Force Fields for Thiolate-Protected Gold Nanoclusters.

1. In the training directory:

all_dft.xyz contains all the coordinates and the corresponded energy information for the structures in the training sets. training.yaml is the input file which contains all the training parameters.

Using the above two files and going through the training process using FLARE++, one can get the same machine learning force-fields as shown in this manuscript.

2. In the validation directory:

Coord sub-directory contains all the optimized structure of gold clusters, those optimized structures have been applied as the starting structure of the molecular dynamics simulations.

MD-frame sub-directory contains the LAMMPS simulation input files and all the structures that we extracted from MD trajectories. We then validated their energy between machine learning and DFT calculations.

Energy sub-directory contains the spreadsheet which includes the information on the energy differences between VASP DFT calculations and machine learning results.





