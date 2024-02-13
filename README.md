# Sparse matrix representation of SNP systems

A simulator of Spiking Neural P systems (SNP) with delays for GPUs using sparse matrix representations. The idea of this code is to test the concepts for sparse matrix representation of SNPs for GPUs. Publication is still pending.

## Compilation

You need the CUDA toolkit 11 or 12 accesible in your system, and a compatible C++ compiler like gcc. Only Linux systems were tested (Ubuntu and Rocky).

1. If you don't have it already, define the PATH to your CUDA HOME, e.g.: `export PATH=/usr/local/cuda-12.1/bin:$PATH`
2. Define where the libraries of CUDA are, e.g.: `export LD_LIBRARY_PATH=/usr/local/cuda-12.1/lib64:$LD_LIBRARY_PATH`
3. Simply type `make` to compile the project. The binary will appear in the `bin` folder.

## Execution

You should see the binary inside `bin` folder. There is a help menu by simply typing `bin/ssnp`. It will help you to reproduce the results of our paper.
