# 2-D Multi-Layer Anomaly Model Inversion Data

This folder contains the model files for Section III-B of the manuscript,
which evaluates PSTD- and FDTD-based FWI at PPW = 3--10.

## Files

- `ppw_03` through `ppw_10`: one folder for each PPW setting. Each
  `model.mat` contains the relative-permittivity model `ep`, conductivity
  model `sig`, coordinates `x` and `z`, grid spacing `dx`, and metadata
  `meta`.
- `ppw_10/datareal.mat`: synthetic observed data generated at 10 PPW. The
  variable `datareal` is an `1885 x 50` single-precision array.

The model grid is refined while the physical domain remains approximately
`1.0 x 0.5 m`, as described in the manuscript. Coordinates are in metres and
conductivity follows the units used in the manuscript. This package contains
data only; source code and inversion results are not included.
