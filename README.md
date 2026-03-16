# Ecosys Modeling of Microbial Activity in a Freshwater Marsh

## Overview
This repository contains code and analysis used to simulate microbial activity and carbon cycling in a freshwater marsh at Old Woman Creek National Estuarine Research Reserve (OWC NERR), Huron, Ohio using the Ecosys process-based ecosystem model.

Model outputs are evaluated using high-frequency electrochemical measurements from a zero-resistance ammetry (ZRA) sensor, which provides near-real-time measurements of microbial electron transfer processes in wetland sediments (via a measurable current). ZRA field measurements used in this project were collected between September and December 2023.

To ensure the model accurately simulated ecosystem carbon dynamics, the model was first calibrated and evaluated using eddy covariance measurements and chamber-based greenhouse gas flux data collected at Old Woman Creek.

---

# What This Project Does

This project integrates process-based ecosystem modeling, field measurements of greenhouse gas fluxes, and electrochemical microbial activity data to evaluate microbial processes in wetland sediments.

Specifically, this repository includes and/or references workflows to:

- Simulate carbon cycling and microbial processes in a freshwater marsh using the ecosys processed-based model.
- Evaluate model performance against greenhouse gas flux measurements collected with chambers and eddy covariance instrumentation.
- Integrate zero-resistance ammetry (ZRA) sensor data to assess microbial electron transfer dynamics in wetland sediments.
- Optimize key model parameters using Bayesian optimization.
- Compare modeled microbial activity (g soil C consumed/hourly) with high-frequency (hourly) electrochemical measurements of microbial activity (current, a proxy for microbial activity). 

---

# Why This Project Is Useful

Wetlands are globally important sources and sinks of greenhouse gases, but microbial processes controlling these fluxes are difficult to observe directly and are often poorly represented in ecosystem models.

This project advances wetland modeling by:

- Improving greenhouse gas modeling in wetlands using a process-based ecosystem model
- Providing one of the first evaluations of microbial processes in a process-based ecosystem model using real, high-frequency microbial activity measurements
- Integrating electrochemical sensor data with ecosystem modeling to better constrain microbial dynamics

By combining ecosystem modeling, Bayesian optimization, and electrochemical microbial measurements, this work provides a new framework for evaluating how microbial activity influences greenhouse gas emissions from wetlands.

---

# Data Used for Model Evaluation

## Chamber Flux Measurements

Hassett E ; Villa J ; Onyango Y ; Eberhard E ; Bohrer G ; Kinsman-Costello L ; Morin T (2023)  
Carbon flux measurements from chambers collected between July to October 2022 at Old Woman Creek, Huron, Ohio.  
Rewriting the Redox Paradigm: Dynamic hydrology shapes nutrient and element transformations in a Great Lakes Coastal Estuary.  
ESS-DIVE Dataset.  
https://doi.org/10.15485/2229438

Hassett E ; Villa J ; Bohrer G ; Kinsman-Costello L ; Eberhard E ; Carnevali J ; Brown M ; Martin S ; Morin T (2025)  
Carbon flux measurements from chambers collected between April to October 2023 at Old Woman Creek, Huron, Ohio.  
ESS-DIVE Dataset.  
https://doi.org/10.15485/3003419

---

## Eddy Covariance Data

Bohrer, G., & Kerns, J. (2024)  
AmeriFlux BASE US-OWC Old Woman Creek, Ver. 5-5.  
AmeriFlux AMP Dataset.  
https://doi.org/10.17190/AMF/1418679

---

# Supporting Publication

The modeling framework builds on previous work:

Hassett E, Bohrer G, Kinsman-Costello L, et al. Changes in inundation drive carbon dioxide and methane fluxes in a temperate wetland. Science of The Total Environment. 2024; 915, 170089. https://doi.org/10.1016/j.scitotenv.2024.170089


---

# Model Parameter Optimization

Model parameters were optimized using Bayesian Optimization for Anything (BOA), an open-source framework designed to make Bayesian optimization accessible for environmental modeling.

Scyphers, M., Missik, J., Kujawa, H., Paulson, J., & Bohrer, G. (2024)  
Bayesian Optimization for Anything (BOA): An open-source framework for accessible, user-friendly Bayesian optimization.  
Environmental Modelling & Software  
https://doi.org/10.1016/j.envsoft.2024.106191

Scyphers, M., Missik, J., Paulson, J., & Bohrer, G. (2024)  
Bayesian Optimization for Anything (BOA) [Computer software]  
https://doi.org/10.5281/zenodo.12797033

---

# Additional Dataset Related to the Microbial Activity

Heard T ; Eberhard E ; Weerasinghe S ; Kinsman-Costello L ; Monty C ; Morin T ; Senko J (2025)  
Old Woman Creek Wetland Sediment and Electrochemical Sensor Microbial Community, 2023  
ESS-DIVE Dataset  
https://doi.org/10.15485/2568076

---

# Study Site

All field measurements were conducted at Old Woman Creek National Estuarine Research Reserve (OWC NERR), a freshwater estuary located along the southern shore of Lake Erie in Huron, Ohio, USA.

---

# Repository Structure
