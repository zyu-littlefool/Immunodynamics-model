# Immunodynamics-model
Simulation code and reference data for reproducing the results reported.



# Code and data for "An immunodynamics-guided adjuvant broadens immunity across viral variants"

This repository contains the simulation code and reference data associated with "An immunodynamics-guided adjuvant broadens immunity across viral variants".

## Quick reproducibility example

The example runs only seed group 15 under all three release modes.
It performs three simulations, corresponding to run43, run44, and run45 in the full 45-simulation experiment. It does not rerun all 15 seed groups.

## Computing environment

The original simulations were performed on a Windows workstation
with the following configuration:

- Processor: 2 × Intel(R) Xeon(R) Platinum 8488C @ 2.40 GHz
- Installed RAM: 1.0 TB
- MATLAB: R2024a
- Required toolbox: Parallel Computing Toolbox

### Run

Open MATLAB in the repository root directory and run:
    run_example
    run_CD8_example
    verify_example

### Expected output

Results are written to:

    output/example_seed15/

Reference outputs are provided in:

    expected_output/example_seed15/

## Full reproduction

To run all 15 seed groups and all three release modes:

    run_full

The full experiment contains 45 simulations.
