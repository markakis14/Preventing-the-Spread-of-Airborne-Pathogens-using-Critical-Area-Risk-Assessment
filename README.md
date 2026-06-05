# Preventing-the-Spread-of-Airborne-Pathogens-using-Critical-Area-Risk-Assessment
# Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment

## Overview

This repository contains the implementation developed for my Diploma Thesis:

**"Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment"**

The project presents an agent-based simulation framework for modeling the spread of airborne pathogens in urban environments. The framework combines realistic city representations, citizen mobility simulation, epidemiological modeling, and dynamic area risk assessment to evaluate pandemic prevention strategies.

The proposed system extends the SARiSsa pandemic simulation framework by introducing a **Critical Area Risk Assessment mechanism** that identifies high-risk locations in real time and enables adaptive behavioral responses from citizens.

---

## Thesis Information

* **Author:** Fotios Markakis
* **Department:** Computer Science & Engineering, University of Ioannina
* **Supervisor:** Stavros D. Nikolopoulos, Polenakis Iosif
* **Year:** 2025

---

## Research Objectives

The goal of this work is to investigate how computational methods can help suppress the spread of airborne pathogens before outbreaks evolve into pandemics.

The framework focuses on:

* Modeling realistic urban environments
* Simulating citizen mobility patterns
* Modeling airborne virus transmission
* Identifying critical high-risk areas
* Evaluating preventive countermeasures
* Studying the effect of behavioral compliance
* Assessing pandemic mitigation strategies

---

## System Architecture

The simulation framework consists of three main components:

### 1. Spatial Model

The spatial model transforms real map images into graph structures representing:

* Streets
* Buildings
* Transportation paths
* Points of interest
* Urban congestion zones

### 2. Mobility Model

The mobility model simulates citizen movement using an agent-based approach.

Features include:

* Daily movement schedules
* Route planning
* Attraction points (hotspots)
* Traffic-aware path selection
* Social interactions between agents

### 3. Propagation Model

The propagation model simulates disease transmission through:

* SIII epidemic states:

  * Susceptible
  * Infected
  * Infectious
  * Immune

* Viral load evolution

* Airborne droplet transmission

* Distance-based infection probability

* Stochastic infection dynamics

---

## Critical Area Risk Assessment

The main contribution of this thesis is the introduction of an Area Risk Assessment mechanism.

The system:

1. Monitors local neighborhoods around citizens.
2. Detects nearby infected and infectious individuals.
3. Computes a local risk index.
4. Identifies critical zones with elevated transmission risk.
5. Enables adaptive behavioral responses.

Citizens classified as **obedient** may:

* Change route
* Avoid dangerous areas
* Return to their origin

Citizens classified as **non-compliant** continue following their original routes.

This allows the study of the relationship between:

* Individual behavior
* Spatial risk distribution
* Epidemic spread dynamics

---

## Evaluated Countermeasures

The framework supports evaluation of:

* Lockdowns
* Density reduction measures
* Contact tracing
* Area risk awareness
* Combined intervention strategies

Simulation results are evaluated using repeated Monte Carlo experiments.

---

## Technologies

* Python
* Jupyter Notebook
* NumPy
* NetworkX
* Matplotlib
* Agent-Based Modeling

---

## Repository Structure

```text
.
├── covid19_sim.ipynb
├── # Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment

## Overview

This repository contains the implementation developed for my Diploma Thesis:

**"Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment"**

The project presents an agent-based simulation framework for modeling the spread of airborne pathogens in urban environments. The framework combines realistic city representations, citizen mobility simulation, epidemiological modeling, and dynamic area risk assessment to evaluate pandemic prevention strategies.

The proposed system extends the SARiSsa pandemic simulation framework by introducing a **Critical Area Risk Assessment mechanism** that identifies high-risk locations in real time and enables adaptive behavioral responses from citizens.

---

## Thesis Information

* **Author:** Fotios Markakis
* **Department:** Computer Science & Engineering, University of Ioannina
* **Supervisor:** Stavros D. Nikolopoulos
* **Year:** 2025

---

## Research Objectives

The goal of this work is to investigate how computational methods can help suppress the spread of airborne pathogens before outbreaks evolve into pandemics.

The framework focuses on:

* Modeling realistic urban environments
* Simulating citizen mobility patterns
* Modeling airborne virus transmission
* Identifying critical high-risk areas
* Evaluating preventive countermeasures
* Studying the effect of behavioral compliance
* Assessing pandemic mitigation strategies

---

## System Architecture

The simulation framework consists of three main components:

### 1. Spatial Model

The spatial model transforms real map images into graph structures representing:

* Streets
* Buildings
* Transportation paths
* Points of interest
* Urban congestion zones

### 2. Mobility Model

The mobility model simulates citizen movement using an agent-based approach.

Features include:

* Daily movement schedules
* Route planning
* Attraction points (hotspots)
* Traffic-aware path selection
* Social interactions between agents

### 3. Propagation Model

The propagation model simulates disease transmission through:

* SIII epidemic states:

  * Susceptible
  * Infected
  * Infectious
  * Immune

* Viral load evolution

* Airborne droplet transmission

* Distance-based infection probability

* Stochastic infection dynamics

---

## Critical Area Risk Assessment

The main contribution of this thesis is the introduction of an Area Risk Assessment mechanism.

The system:

1. Monitors local neighborhoods around citizens.
2. Detects nearby infected and infectious individuals.
3. Computes a local risk index.
4. Identifies critical zones with elevated transmission risk.
5. Enables adaptive behavioral responses.

Citizens classified as **obedient** may:

* Change route
* Avoid dangerous areas
* Return to their origin

Citizens classified as **non-compliant** continue following their original routes.

This allows the study of the relationship between:

* Individual behavior
* Spatial risk distribution
* Epidemic spread dynamics

---

## Evaluated Countermeasures

The framework supports evaluation of:

* Lockdowns
* Density reduction measures
* Contact tracing
* Area risk awareness
* Combined intervention strategies

Simulation results are evaluated using repeated Monte Carlo experiments.

---

## Technologies

* Python
* Jupyter Notebook
* NumPy
* NetworkX
* Matplotlib
* Agent-Based Modeling

---

## Repository Structure

```text
.
├── covid19_sim.ipynb
├── Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment.pdf
├── data/
├── Integrated Simulation Framework V 1.4.x/  
└── README.md
```

---

## Running the Simulation

```bash
git clone https://github.com/yourusername/repository-name.git

cd repository-name

jupyter notebook covid19_sim.ipynb
```

Follow the notebook cells sequentially to reproduce the simulation experiments.

---

## Results

The framework demonstrates that:

* Early intervention significantly reduces viral spread.
* Area Risk Assessment improves exposure avoidance.
* Behavioral compliance influences epidemic outcomes.
* Combining multiple countermeasures produces the strongest mitigation effects.

---

## Future Work

Possible extensions include:

* Multi-city simulations
* Real-time GIS integration
* Vaccination strategies
* Reinforcement learning for adaptive routing
* Real mobility datasets
* Additional epidemiological models

---

## Citation

If you use this work, please cite:

```bibtex
@mastersthesis{markakis2025,
  author = {Fotios Markakis},
  title = {Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment},
  school = {University of Ioannina},
  year = {2025}
}
```

---

## License

This project is provided for academic and research purposes.
.pdf
├── data
├── results
└── README.md
```

---

## Running the Simulation

```bash
git clone https://github.com/yourusername/repository-name.git

cd repository-name

jupyter notebook covid19_sim.ipynb
```

Follow the notebook cells sequentially to reproduce the simulation experiments.

---

## Results

The framework demonstrates that:

* Early intervention significantly reduces viral spread.
* Area Risk Assessment improves exposure avoidance.
* Behavioral compliance influences epidemic outcomes.
* Combining multiple countermeasures produces the strongest mitigation effects.

---

## Future Work

Possible extensions include:

* Multi-city simulations
* Real-time GIS integration
* Vaccination strategies
* Reinforcement learning for adaptive routing
* Real mobility datasets
* Additional epidemiological models

---

## Citation

If you use this work, please cite:

```bibtex
@mastersthesis{markakis2025,
  author = {Fotios Markakis},
  title = {Preventing the Spread of Airborne Pathogens using Critical Area Risk Assessment},
  school = {University of Ioannina},
  year = {2025}
}
```

---

## License

This project is provided for academic and research purposes.
