# PSTD-FWI Simulation Data

This directory contains the MATLAB data associated with the manuscript
*Memory-Efficient 3-D Ground-Penetrating Radar Full-Waveform Inversion
Based on Staggered-Grid Pseudospectral Time-Domain Modeling*.

The subdirectories correspond to the numerical experiments in Section III:

- `01_3d_forward_modeling_validation`: Section III-A, 3-D forward-modeling validation. It contains the synthetic 3-D material model and Ez waveform comparisons between PSTD and FDTD for PPW = 3--10.
- `02_2d_multilayer_anomaly_model_inversion`: Section III-B, 2-D multi-layer anomaly model inversion. It contains model files for PPW = 3--10 and the synthetic observed data for the 10-PPW case.
- `03_3d_undulating_layered_model_inversion`: Section III-C, 3-D undulating layered model inversion. It contains the 4-PPW and 6-PPW model files used for the PSTD/FDTD comparison.

The files are provided in MATLAB MAT format. Spatial coordinates are in metres;
time and electrical-field units follow the conventions of the manuscript and
the corresponding solver output. Source code and field-data files are not
included in this data package.
