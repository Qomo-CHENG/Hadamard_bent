# Self-dual bent sequences in Hadamard matrices

This repo is created for presenting various Hadamard matrices and corresponding numerical solutions of self-dual bent seuqnces. It is the open-source of the paper `Self-dual Hadamard bent sequences`, which is submitted to *IEEE Transactions on XXX*.

- [x] Special thanks to Patrick Solé and Dean Crnković for constructing and sharing those Hadamard matrices.

<br/>

## Hadamard matrices at different orders

***Note that: SD for self-dual; seqs for sequences; Refs for references**

### Order 16

- Sylvester type
- Number of matrices: 1 [*link*](./Hadamard_matrices/H_n16_eigen4_Sylvester_N1.txt)
- Number of SD bent seqs: 140 [*link*](./bent_sequences/sd_bent_n16_eigen4_Sylvester_N1.log)
- Refs: the first Hadamard matrix in [*Magma*](http://magma.maths.usyd.edu.au/magma/)

### Order 36

- Bush Type
  - Number of matrices: 29 [*link*](./Hadamard_matrices/H_n36_eigen6_Bush_N29.txt)
  - Number of SD bent seqs: 64 [*link*](./bent_sequences/sd_bent_n36_eigen6_Bush_N29.log)
  - Refs: 
    - Z. Janko, The existence of a Bush-type Hadamard matrix of order 36 and two new infinite classes of symmetric designs, J. Combin. TheorySer. A 95 (2001), 360–364.
    - Z. Janko, H. Kharaghani, A block negacyclic Bush-type Hadamard matrix and two strongly regular graphs, J. Combin. Theory Ser. A 98 (2002), 118–126.
- Paley Type
  - Number of matrices: 1 [*link*](./Hadamard_matrices/H_n36_eigen6_Paley_N1.txt)
  - Number of SD bent seqs: 204 [*link*](./bent_sequences/sd_bent_n36_eigen6_Paley_N1.log)
  - Refs: 
    - P., Solé, W., Cheng, S., Guilley, O., Rioul, Bent Sequences over Hadamard Codes for Physically Unclonable Functions. ISIT 2021: 801-806 (2021).

### Order 64

- pending

### Order 100

- pending

### Order 144

- Bush type
- Number of matrices: 4 [*link*](./Hadamard_matrices/H_n144_eigen12_Bush_N4.txt)
- Number of SD bent seqs: 20, 924 or 1052 [*link*](./bent_sequences/sd_bent_n144_eigen12_Bush_N4.log)
- Refs: 
  - D. Crnković, A Construction of Some Symmetric (144,66,30) Designs, J. Appl. Algebra Discrete Struct. 5, No. 1 (2007), 33-39.
  - M.-O. Pavčević, Symmetric designs of Menon series admitting an action of Frobenius groups, Glas. Mat., III. Ser. 31 (1996), 209-223.


### Order 196

- Regular type
- Number of matrices: 4 [*link*](./Hadamard_matrices/H_n196_eigen14_Regular_N4.txt)
- Number of SD bent seqs: 6864 or 12870 [*link*](./bent_sequences/sd_bent_n196_eigen14_Regular_N4.log)
- Refs: 
  - D. Crnković, A Construction of Some Symmetric Designs with Parameters (196,91,42), Int. Math. Forum 2, No. 61 (2007), 3021-3026.


<br/>

## Copyright and License

This repository is placed into the public domain. Anyone can redistribute it and/or modify it under the terms of the [GNU General Public License version 3.0](https://www.gnu.org/licenses/gpl-3.0.html).

Copyright (C) 2022. All Rights Reserved to Authors.
