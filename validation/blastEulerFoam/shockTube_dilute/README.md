# Validation of dilute granular

## Notes

This case uses a single granular phases within a continuous air phase. This a dilute simulation where packing of particles does not occur. The continuous gas phase is represented by air, and the particle phase have a density of 2500 kg/m^3, a coefficient of restitution of 0.999, and a diameter of 10e-6.

Original plots were digitized using WebPlotDigitizer: https://github.com/ankitrohatgi/WebPlotDigitizer/releases The quality of the plots in the original publication (below) was not ideal for reproduction, but we have made an effort to reproduce them as faithfully as possible, and the points are found in the "validation/validationData" directory.

The calculation took approx. 8 s to run on a single core laptop at the reference resolution (e.g. 400 cells). Reference solution and plots from this run are in the "validation/referencePlots" directory. Plots will be automatically created using the postProcess and createGraphs utilities for subsequent runs.

## Reference

```
Houim, R.W., Oran, E.S., 2016. A multiphase model for compressible granular–gaseous flows: formulation and initial tests. Journal of Fluid Mechanics 789, 166–220. https://doi.org/10.1017/jfm.2015.728


```
