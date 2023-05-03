# Quantum algorithm for protein structure prediction

A Qiskit implementation of a quantum algorithm for protein structure prediciton in 2D hydrophobic-hydrophilic model. This notebook contains the accompanying code for the paper in [1]. 


# Status
This notebook is incomplete and under active development. 

# Notes on use
For simplicity, this notebook requires the user to change manually the variable j specifying the expected energy (= number of hydrophobic-hydrophobic contacts in the lattice). The present value of j is 1 as this is the expected energy level for the amino acid sequence PHPPH (encoded as 01001). 

# Acknowledgement
This notebook is based on the theory described in [1].

The code was written by Renata Wong (https://orcid.org/0000-0001-5468-0716).

This work benefited greatly from discussions with Prof. Weng-Long Chang (National Kaohsiung University of Science and Technology) and Dr. Aoyu Zhang (AWS). All remaining deficiencies are my own.

# References
[1] R. Wong and W-L. Chang, "Fast quantum algorithm for protein structure prediction in hydrophobic-hydrophilic model", Journal of Parallel and Distributed Computing 164:178-190, 2022, DOI: 10.1016/j.jpdc.2022.03.011.
