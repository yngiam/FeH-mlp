This folder contains example input files used to reproduce the molecular dynamics (MD) simulations of crack propagation described in the associated publication.

## Input Files

Two LAMMPS input scripts are provided in the root directory:

- `with_H_input_example.lmpin` — simulates crack propagation with hydrogen  
- `without_H_input_example.lmpin` — simulates crack propagation without hydrogen  

These scripts use the initial structure files located in the subfolders and generate the following output files:

1. `forces.dat` — contains forces used for stress calculations  
2. `crack.dump` — LAMMPS dump file for visualization

## Initial Structure Files

Initial model files are organized in subfolders named according to the crack orientation. For example:

- `100_001/` — corresponds to a crack with (100)[001] orientation

Each structure file includes the hydrogen concentration in its filename. For instance:

- `crack_H_261.lmp` — represents a crack model with 26.1% hydrogen concentration

## Notes

- Random seeds are not included in the input scripts.  
- Minor deviations from the published results may occur due to stochastic effects in MD simulations.

