# jmakLaplacianFoam

Solver for time-temperature reactive heat release in solids.

Implements differential Johnson–Mehl–Avrami–Kolmogorov (JMAK) reaction progress kinetics for non-isothermal process as proposed by [Mittemeijer et al.](https://doi.org/10.1007/BF02628377).

Implemented and tested with [OpenFOAM v2212](https://www.openfoam.com/news/main-news/openfoam-v2212).

## To-do's

- [ ] Document build instructions and usage.
- [ ] Generalization for an arbitrary number of reactions.
- [ ] Implement `solidThermo` to use `externalWallHeatFluxTemperature`.
