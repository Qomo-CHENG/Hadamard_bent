# Self-dual bent sequences in Hadamard matrices

This repo is created for presenting various Hadamard matrices and corresponding numerical solutions of self-dual bent seuqnces. It is the open-source of the paper `Self-dual Hadamard bent sequences`, which is submitted to *IEEE Transactions on XXX*.

- [x] Special thanks to Patrick Solé and Dean Crnković for constructing and sharing those Hadamard matrices.

<br/>

## Hadamard matrices at different orders

***Note that: SD for self-dual; seqs for sequences; Refs for references**

### Order 16

- Sylvester type
- Number of matrices: 1 [*link.*](./Hadamard_matrices/H_n16_eigen4_Sylvester_N1.txt)
- Number of SD bent seqs: 140 [*link.*](./bent_sequences/sd_bent_n16_eigen4_Sylvester_N1.log)
- Refs: the first Hadamard matrix in [*Magma*](http://magma.maths.usyd.edu.au/magma/)

### Order 36

- Bush Type
  - Number of matrices: 29 [*link.*](./Hadamard_matrices/H_n36_eigen6_Bush_N29.txt)
  - Number of SD bent seqs: 64 [*link.*](./bent_sequences/sd_bent_n36_eigen6_Bush_N29.log)
  - Refs: 
    - Z. Janko, "The existence of a Bush-type Hadamard matrix of order 36 and two new infinite classes of symmetric designs," J. Comb. Theory, Ser. A, vol. 95, no. 2, pp. 360-364, Aug. 2001.
    - Z. Janko and H. Kharaghani, "A block negacyclic Bush-type Hadamard matrix and two strongly regular graphs," J. Comb. Theory, Ser. A, vol. 98, no. 1, pp. 118-126, Apr. 2002, DOI: 10.1006/jcta.2001.3231.
- Paley Type
  - Number of matrices: 1 [*link.*](./Hadamard_matrices/H_n36_eigen6_Paley_N1.txt)
  - Number of SD bent seqs: 204 [*link.*](./bent_sequences/sd_bent_n36_eigen6_Paley_N1.log)
  - Refs: 
    - P. Solé, W. Cheng, S. Guilley, and O. Rioul, "Bent sequences over Hadamard codes for physically unclonable functions," in IEEE International Symposium on Information Theory, Melbourne, Australia, July 12-20, 2021. IEEE, 2021, pp. 801-806, DOI: 10.1109/ISIT45174.2021.9517752.

### Order 64

- pending



### Order 100

- Regular type
  - Number of matrices: 120 [*link.*](./Hadamard_matrices/H_n100_eigen10_Regular_N120.txt)
  - Number of SD bent seqs: 1024, 1056, 1152, 1216, 1312, 1536, 1986, 2304, 2336, 2432, 2496, 2576, 2592, 3584, 3712, 3616, 5312, or 6464  [*download.*](./bent_sequences/sd_bent_n100_eigen10_Regular_N120.zip)
  - Refs: 
    - D. Crnković, R. Egan, and A. Švob, "Orbit matrices of Hadamard matrices and related codes," Discrete Math., vol. 341, no. 5, pp. 1199-1209, May 2018.

- Regular type
  - Number of matrices: 1 [*link.*](./Hadamard_matrices/H_n100_eigen10_Regular_N1.txt)
  - Number of SD bent seqs: 12  [*link.*](./bent_sequences/sd_bent_n100_eigen10_Regular_N1.log)
  - Refs: 
    - M.-O. Pavčević, "Symmetric designs of Menon series admitting an action of Frobenius groups," Glas. Mat., III. Ser., vol. 31, no. 2, pp. 209-223, Dec. 1996. [Online]. Available: http://books.google.com/books?id=wdgsTPYo92YC&pg=PA209

- Regular Menon type
  - Number of matrices: 4 [*link.*](./Hadamard_matrices/H_n100_eigen10_Regular_Menon_N4.txt)
  - Number of SD bent seqs: 12  [*link.*](./bent_sequences/sd_bent_n100_eigen10_Regular_Menon_N4.log)
  - Refs: 
    - D. Crnković, R. Egan, and A. Švob, "Orbit matrices of Hadamard matrices and related codes," Discrete Math., vol. 341, no. 5, pp. 1199-1209, May 2018.

### Order 144

- Bush type
- Number of matrices: 4 [*link.*](./Hadamard_matrices/H_n144_eigen12_Bush_N4.txt)
- Number of SD bent seqs: 20, 924 or 1052 [*link.*](./bent_sequences/sd_bent_n144_eigen12_Bush_N4.log)
- Refs: 
  - D. Crnković, A Construction of Some Symmetric (144,66,30) Designs, J. Appl. Algebra Discrete Struct. 5, No. 1 (2007), 33-39.
  - M.-O. Pavčević, Symmetric designs of Menon series admitting an action of Frobenius groups, Glas. Mat., III. Ser. 31 (1996), 209-223.


### Order 196

- Regular type
- Number of matrices: 4 [*link.*](./Hadamard_matrices/H_n196_eigen14_Regular_N4.txt)
- Number of SD bent seqs: 6864 or 12870 [*link.*](./bent_sequences/sd_bent_n196_eigen14_Regular_N4.log)
- Refs: 
  - D. Crnković, A Construction of Some Symmetric Designs with Parameters (196,91,42), Int. Math. Forum 2, No. 61 (2007), 3021-3026.


<br/>

## Copyright and License

This repository is placed into the public domain. Anyone can redistribute it and/or modify it under the terms of the [GNU General Public License version 3.0](https://www.gnu.org/licenses/gpl-3.0.html).

Copyright (C) 2022. All Rights Reserved to Authors.
