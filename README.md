## AD-HTC FUEL ENHANCED GAS CYCLE 
## Overview
This repository contains the simulation models, thermodynamic data, and performance analysis tools for the **Auto-thermal Decomposition Hydrogen-Transfer Cycle (AD-HTC)** fuel enhanced gas cycle power plant. 

The AD-HTC is an advanced power generation cycle designed to maximize thermal efficiency and reduce carbon intensity by integrating fuel reforming (decomposition) with the gas turbine cycle. By utilizing the waste heat from the turbine exhaust to drive the endothermic decomposition of fuels (such as Natural Gas or Methanol), the system produces a hydrogen-rich synthesis gas. This enrichment enhances combustion stability, allows for higher turbine inlet temperatures (TIT), and improves the overall exergetic efficiency of the plant.

## Key Features
- **Exhaust Heat Recovery:** Integrated heat exchange network that recovers low-grade heat to drive the AD-HTC unit.
- **Hydrogen Enrichment:** In-situ production of H2-rich fuel to lower ignition limits and improve flame speed.
- **Advanced Gas Turbine Integration:** Models for high-pressure ratios and cooling requirements for hydrogen-rich combustion.
- **Reduced Emissions:** Lower NOx and CO2 profiles compared to standard Brayton cycles due to improved combustion chemistry and efficiency.
- **Dynamic Simulation:** Support for load-following and transient response analysis.

## Technical Specifications & Architecture

### 1. Cycle Configuration
The system consists of the following primary sub-systems:
* **Compressor Station:** Multi-stage compression with optional intercooling.
* **AD-HTC Reactor:** A catalytic reformer/decomposer where primary fuel is mixed with steam or recirculated exhaust and converted via the auto-thermal decomposition process.
* **Combustor:** Optimized for H2-blended fuels with high adiabatic flame temperatures.
* **Gas Turbine:** Multi-stage expansion with blade cooling models.
* **Heat Recovery Steam Generator (HRSG) / Recuperator:** Provides the thermal energy required for the fuel enhancement process.

