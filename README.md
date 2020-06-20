# quantum-psp
Task: Developing Python code for my quantum algorithms for protein structure prediction. 

The code presented here is partly included in my dissertation "Application of Quantum Computing to ab initio Protein Structure Prediction" (February, 2020). It implements in part (due to the fact that the required qubit capacity exceeds the currently available capacity) two quantum algorithms for PSP I co-authored with Prof. Weng-Long Chang of National Kaohsiung University of Applied Sciences. This project is ongoing. 

**_ccrca-circuit-2bit_**: implementation of doubly controlled quantum ripple-carry adder for sequences of length 2

**_ccrca-circuit-3bit_**: implementation of doubly controlled quantum ripple-carry adder for sequences of length 3

**_ccrca-nbit_**: implementation of doubly controlled quantum ripple-carry adder for arbitrary sequences of length greater than 3 (modified from Cuccaro et al, https://arxiv.org/abs/quant-ph/0410184, skips the most significant summation bit)

**_4-qubit-Grover-with-ancilla-bit_**: my implementation of Grover's algorithm for 4 qubits that uses one ancilla bit. The marked solution is 1001. 

**_psp-2d-2bit-generate-conformational-space_**: implementation of an algorithm for generating conformational space for sequences of length 2 in two-dimensional model

**_psp-2d-3bit-generation-of-conformational-space_**: implementation of an algorithm for generating conformational space for sequences of length 3 in two-dimensional model
