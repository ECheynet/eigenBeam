# Eigen-value calculation of continuous beams
[![View eigen-value calculation of continuous beams on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/52075-eigen-value-calculation-of-continuous-beams)
[![DOI](https://zenodo.org/badge/262413587.svg)](https://zenodo.org/badge/latestdoi/262413587)


[![Donation](https://camo.githubusercontent.com/a37ab2f2f19af23730565736fb8621eea275aad02f649c8f96959f78388edf45/68747470733a2f2f77617265686f7573652d63616d6f2e636d68312e707366686f737465642e6f72672f316339333962613132323739393662383762623033636630323963313438323165616239616439312f3638373437343730373333613266326636393664363732653733363836393635366336343733326536393666326636323631363436373635326634343666366536313734363532643432373537393235333233303664363532353332333036313235333233303633366636363636363536353264373936353663366336663737363737323635363536653265373337363637)](https://www.buymeacoffee.com/echeynet)


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
