# eigenBeam
[![View eigen-value calculation of continuous beams on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/52075-eigen-value-calculation-of-continuous-beams)
[![DOI](https://zenodo.org/badge/262413587.svg)](https://zenodo.org/badge/latestdoi/262413587)


## Summary

The eigenfrequencies and mode shapes of a simple beam are calculated based on [1].  During the calculation procedure, It is assumed that:
  - There is no structural coupling between the different degrees of freedom of the beam
  - The beam is homogeneous
  - The beam is un-damped
  - there are free oscillations

Four boundaries conditions are included:
  - pinned-pinned
  - clamped-free
  - clamped-clamped
  - clamped-pinned
  
Two Geometries are available:
  - rectangular beam
  - cylinder

## Content:

  - eigenModes.m: a function used to compute the eigenfrequencies and modes shapes of a continuous beam with different boundaries conditions.
  - Example.m is an application of this function.

## References
[1] Engineering vibration, Daniel J. Inman (3rd edition), near page 500
