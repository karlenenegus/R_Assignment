## R_Assignment

The contents of this folder and how theses files were derived is further described in Assignment.rmd and Assignment.html. This directory contains files & folders which fulfill the R assignment for the class BCB 546x during the Spring 2022 semester. The `maize` directory contains maize genotype data, and the `teosinte` directory contains teosinte genotype data. Concatenated versions of the genotypes contained in those folders are available in this directory as `maize_genotype_positions.txt` and `teosinte_genotype_positions.txt`.

Within the 'Maize' and 'Teosinte' directories, each numerical chromosome group was written to two files. One file (designated "asc.txt") contains SNPs located on the chromosome in ascending order of physical position with unknown genotypes formatted as ?/?. The second file ("desc.txt") contains the same SNPs in descending order with unknown genotypes formatted as -/-.

An example of a complete file name is "maize_chr_10_desc.txt". This file contains genotypes from maize group samples which are located on chromosome 10 and are sorted in descending order. If the chromosome group was a non-numeric type only one file was written.

Files containing SNPs of unknown or multiple positions (ex: "teosinte_chr_unknown.txt") are not sorted, and unknown genotypes are stored as ?/?. Files containing maize group genotype beginning in "maize" and are written to the ./maize directory. Teosinte files have been stored in a likewise fashion.

Finally, SNPs which were mapped to a specific chromosome but still list the position as "multiple" were treated identically to SNPs which had the chromosome designated as "multiple" and are not contained within their respective chromosome files.
