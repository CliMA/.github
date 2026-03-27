# Welcome to the Climate Modeling Alliance (CliMA)

### Building the next generation of climate models.

---

## 🙋‍♀️ What is CliMA?

We are an alliance of scientists, engineers, and applied mathematicians building a new generation of Earth system models (ESMs), entirely written in [Julia](https://julialang.org/). Our mission is to pioneer a new, **data-informed** and **physics-based** approach to climate modeling.

We are developing a model that:
* Learns from the wealth of Earth observations from space and from the ground.
* Runs efficiently on modern computing architectures with GPUs.
* Delivers actionable predictions, from sub-seasonal to decadal scales, to inform critical decisions in risk management and infrastructure and resource planning.

Our goal is to set a new standard in the accuracy, usability, and scalability of climate models.

## 📦 Overview of Key Repositories

**Core Model Components**
* **[ClimaAtmos.jl](https://github.com/CliMA/ClimaAtmos.jl)**: An atmosphere model leveraging data assimilation and machine learning for modeling and calibrating subgrid-scale processes.
* **[ClimaLand.jl](https://github.com/CliMA/ClimaLand.jl)**: A modular land surface model capable of standalone or integrated simulations (e.g., hydrology, canopy, snow, and soil CO2).
* **[ClimaCore.jl](https://github.com/CliMA/ClimaCore.jl)**: The dynamical core of the atmosphere and land models, providing discretization tools to solve their governing equations.
* **[Oceananigans.jl](https://github.com/CliMA/Oceananigans.jl)**: A fast and flexible dynamical core of the ocean model, solving the fluid dynamical equations on CPUs and GPUs.
* **[ClimaSeaIce.jl](https://github.com/CliMA/ClimaSeaIce.jl)**: Coupled and stand-alone simulations of sea ice freezing, melting, and horizontal motion for Earth system modeling.
* **[ClimaCoupler.jl](https://github.com/CliMA/ClimaCoupler.jl)**: The coupler bringing atmosphere, land, ocean, and sea ice models together for global climate simulations (CMIP/AMIP).
* **[CloudMicrophysics.jl](https://github.com/CliMA/CloudMicrophysics.jl)**: A library of cloud microphysics and aerosol parameterizations for high-performance climate simulations.
* **[RRTMGP.jl](https://github.com/CliMA/RRTMGP.jl)**: A Julia implementation of Radiative Transfer for Energetics (RTE) and the RRTMGP optics.

**Shared Physics & Numerics**
* **[ClimaTimeSteppers.jl](https://github.com/CliMA/ClimaTimeSteppers.jl)**: GPU-ready IMEX and multirate ODE solvers tailored for large-scale scientific models.
* **[Thermodynamics.jl](https://github.com/CliMA/Thermodynamics.jl)**: Moist thermodynamic formulations shared across the CliMA ecosystem.
* **[SurfaceFluxes.jl](https://github.com/CliMA/SurfaceFluxes.jl)**: Calculates surface exchange fluxes between model components (e.g., land-atmosphere, ocean-atmosphere).

**Calibration & Uncertainty Quantification**
* **[CalibrateEmulateSample.jl](https://github.com/CliMA/CalibrateEmulateSample.jl)**: A machine-learning-accelerated pipeline for calibration and uncertainty quantification of computationally expensive models.
* **[EnsembleKalmanProcesses.jl](https://github.com/CliMA/EnsembleKalmanProcesses.jl)**: Optimization and approximate uncertainty quantification algorithms based on Ensemble Kalman methods.
* **[ClimaCalibrate.jl](https://github.com/CliMA/ClimaCalibrate.jl)**: Calibration pipelines for CliMA model components.
* **[ClimaParams.jl](https://github.com/CliMA/ClimaParams.jl)**: A single source of truth for physical constants and tunable model parameters across the CliMA ecosystem.

**Tooling & Diagnostics**
* **[ClimaComms.jl](https://github.com/CliMA/ClimaComms.jl)**: A unified interface for diverse computing devices and distributed environments (CPUs/GPUs, single-process/MPI).
* **[ClimaUtilities.jl](https://github.com/CliMA/ClimaUtilities.jl)**: Shared utilities for the CliMA project, supporting, for example, time management and MPI-safe artifact downloading and data handling.
* **[ClimaDiagnostics.jl](https://github.com/CliMA/ClimaDiagnostics.jl)**: A framework to define and output observables and statistics from CliMA simulations.
* **[ClimaAnalysis.jl](https://github.com/CliMA/ClimaAnalysis.jl)**: An analysis library to post-process and visualize ClimaAtmos simulations and NetCDF files.

---

## 🚀 Getting Started

Each repository contains extensive documentation, including examples and tutorials. Visit the documentation links in individual repos to get started, or explore our website at **[clima.caltech.edu](https://clima.caltech.edu)** for an overview of the project.

---

## 📄 Publications

A full list of publications is available at **[clima.caltech.edu/publications](https://clima.caltech.edu/publications/)**.

---

## 🤝 Our Supporters

The Climate Modeling Alliance is a coalition of partners from **Caltech**, **MIT**, and **NASA's Jet Propulsion Laboratory (JPL)**.

Our current work is generously supported by:

* **[Schmidt Sciences](https://www.schmidtsciences.org/)**
* **[U.S. National Science Foundation (NSF)](https://www.nsf.gov/)**
* **[U.S. Office of Naval Research (ONR)](https://www.onr.navy.mil/)**
* **[Resnick Sustainability Institute (RSI)](https://resnick.caltech.edu/)**

Learn more about our mission, our team, and our science at **[clima.caltech.edu](https://clima.caltech.edu)**.
