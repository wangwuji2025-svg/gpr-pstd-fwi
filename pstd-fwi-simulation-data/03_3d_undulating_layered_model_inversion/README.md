# 3-D Undulating Layered Model Inversion Data

This folder contains the model files for Section III-C of the manuscript,
the 3-D undulating layered model inversion experiment.

## Files

- `ppw_04/model.mat`: PSTD model at 4 PPW.
- `ppw_06/model.mat`: model at 6 PPW used for the PSTD/FDTD comparison.

Each MAT file contains the true and initial relative-permittivity models
(`ep`, `ep_init`), conductivity models (`sig`, `sig_init`), spatial
coordinates, grid dimensions, and the PPW value (`ppw_case`). The model
domain and acquisition settings follow the manuscript. Coordinates are in
metres and conductivity uses the units reported in the manuscript.
