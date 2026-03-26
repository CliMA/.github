# Welcome to the Climate Modeling Alliance (CliMA)

### Building the next generation of climate models.

---

We are an alliance of scientists, engineers, and applied mathematicians building a new generation of Earth system models (ESMs). Our mission is to pioneer a new, **data-informed** and **physics-based** approach to climate modeling.

We are developing a model that:
* Learns from the wealth of Earth observations from space and from the ground.
* Runs efficiently on modern computing architectures with GPUs.
* Delivers actionable predictions, from sub-seasonal to decadal scales, to inform critical decisions in risk management and infrastructure and resource planning.

Our goal is to set a new standard in the accuracy, usability, and scalability of climate models.

## 📦 Overview of Key Repositories

**Core Model Components**
* **[ClimaAtmos.jl](https://github.com/CliMA/ClimaAtmos.jl)**: An atmosphere model leveraging data assimilation and machine learning for modeling subgrid-scale processes.
* **[ClimaLand.jl](https://github.com/CliMA/ClimaLand.jl)**: A modular land surface model capable of standalone or integrated simulations (e.g., hydrology, canopy, snow, and soil CO2).
* **[ClimaCore.jl](https://github.com/CliMA/ClimaCore.jl)**: The dynamical core providing flexible spatial discretization tools to solve the governing equations of the atmosphere and land models.
* **[Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl)**: A fast and flexible ocean model.
* **[ClimaSeaIce.jl](https://github.com/CliMA/ClimaSeaIce.jl)**: Coupled and stand-alone simulations of sea ice freezing, melting, and horizontal motion.
* **[ClimaCoupler.jl](https://github.com/CliMA/ClimaCoupler.jl)**: The coupler bringing atmosphere, land, ocean, and sea ice models together for global climate simulations (CMIP/AMIP).
* **[CloudMicrophysics.jl](https://github.com/CliMA/CloudMicrophysics.jl)**: A library of bulk cloud microphysics and aerosol parameterizations for high-performance climate simulations.
* **[RRTMGP.jl](https://github.com/CliMA/RRTMGP.jl)**: A Julia implementation of the Rapid Radiative Transfer Model for General circulation model applications–Parallel.

**Infrastructure**
* **[ClimaTimeSteppers.jl](https://github.com/CliMA/ClimaTimeSteppers.jl)**: GPU-ready IMEX and multirate ODE solvers tailored for large-scale scientific models.
* **[Thermodynamics.jl](https://github.com/CliMA/Thermodynamics.jl)**: Thermodynamics shared across the CliMA ecosystem to ensure energetic consistency. 
* **[SurfaceFluxes.jl](https://github.com/CliMA/SurfaceFluxes.jl)**: Calculates surface exchange fluxes between model components (e.g., land-atmosphere, ocean-atmosphere).
* **[ClimaComms.jl](https://github.com/CliMA/ClimaComms.jl)**: Tools for distributed computing and device-specific configurations.
* **[CalibrateEmulateSample.jl](https://github.com/CliMA/CalibrateEmulateSample.jl)**: Tools calibration and uncertainty quantification of computationally expensive models (such as ESMs).
* **[ClimaCalibrate.jl](https://github.com/CliMA/ClimaCalibrate.jl)**: Calibration pipelines for CliMA model components.
* **[ClimaParams.jl](https://github.com/CliMA/ClimaParams.jl)**: Single source of truth for all adjustable model parameters.
* **[ClimaUtilities.jl](https://github.com/CliMA/ClimaUtilities.jl)**: Shared utilities for the CliMA project, supporting, for example, time management and MPI-safe artifact downloading and data handling.
* **[ClimaDiagnostics.jl](https://github.com/CliMA/ClimaDiagnostics.jl)**: A framework to define and output observables and statistics from CliMA simulations.
* **[ClimaAnalysis.jl](https://github.com/CliMA/ClimaAnalysis.jl)**: An analysis library to post-process and visualize ClimaDiagnostics outputs and NetCDF files.
  
---

## 🤝 Our Supporters

The Climate Modeling Alliance is a coalition of partners from **Caltech**, **MIT**, and **NASA's Jet Propulsion Laboratory (JPL)**.

Our current work is generously supported by:

* **[Schmidt Sciences](https://www.schmidtsciences.org/)**
* **[U.S. National Science Foundation (NSF)](https://www.nsf.gov/)**
* **[Department of Defense/Office of Naval Research](https://www.onr.navy.mil/)**
* **[Resnick Sustainability Institute (RSI)](https://resnick.caltech.edu/)**

Learn more about our mission, our team, and our science at **[clima.caltech.edu](https://clima.caltech.edu)**.
