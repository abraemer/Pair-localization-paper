# Pair localization in dipolar systems with tunable positional disorder

This repo contains all the code that was directly involved in the creation of the paper.

## Contents

- `XXZPaper`: contains the scripts with the chosen parameters for running the simulations on the [JUSTUS2 cluster](https://www.uni-ulm.de/einrichtungen/kiz/service-katalog/high-performance-computing/justus2/). Also plotting script.
- `SimLib.jl`: contains code for computing various spectral indicators and saving/loading the data. (Needs cleanup)
- `XXZNumerics.jl`: just some basics for and constructing and working with Heisenberg type spin models
- `SpinSymmetry.jl`: technically not needed to be added here as it's also in Julia's registry. Small package to project on symmetry sectors of spin models. One can combine any symmetries one wants.
- `FilteredMatrices.jl`: Written by [Github user pablosanjose](https://github.com/pablosanjose). Technically not used for the paper simulations, but a dependency of `SimLib.jl`, so included for completeness' sake.
