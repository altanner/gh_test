# MoSuMa_tools
A perl script pipeline for compiling molecular supermatrices.

Initially, this pipeline deals with two input file: a list of genes (or other sequence data) as BLAST targets, and an assembled transcriptome in which to BLAST search. Data can be in amino acids or nucleotides. Outputs are aligned matrices for each sequence, ready for concatenation into a supermatrix, gene-tree analysis, or anything else really.

In future this pipeline will be able to deal with genomic input files. It will also be possible to fully automate the pipeline in situations where human interaction to check correct operation is unnecessary.

Please report all bugs to jairly (al.tanner@gmail.com)
