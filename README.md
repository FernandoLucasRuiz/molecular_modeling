# Molecular Modeling MSc Bioinformatics

## Introduction

This repository contains the molecular dynamics simulation data and analysis for the AQA tripeptide, conducted using GROMACS, a powerful simulation tool for biochemical molecules. The project focuses on understanding the behavior of the tripeptide under various environmental conditions and its implications in biophysics and biochemistry.

## Model Construction

The tripeptide AQA is modeled starting from generating its cubic cellular unit to thermodynamic analysis. This section illustrates the necessary setup before diving into the thermodynamic behavior of the model. The molecule consists of two alanine residues and a central glutamine. A detailed procedure is followed to generate the topology required for GROMACS to interpret the structure.

## Equilibration Phase

The equilibration phase is crucial to simulate our molecule at specific temperatures which allows for the analysis of energies and atomic velocities under varied conditions. Two specific temperature levels, 298K and 400K, are used to prepare molecular models for subsequent analysis.

## Analysis

The simulation trajectories for both temperature models are analyzed for temperature stability, total and kinetic energy, radius of gyration, bond distances, bond angles, dihedral angles, and atomic velocities.

## Extended Analysis

An additional model with an extended equilibration time is constructed to explore the thermodynamics further. This involves modifying the run NVT.mdp file to reflect longer simulation times.


## Results

The outcomes of the simulations are discussed extensively in the report, where temperature stability, changes in energy, and molecular conformation are

explored. Key findings include the effects of temperature on the structure and dynamics of the tripeptide, including energy distributions, conformational preferences, and atomic movement.

## Contributing

Contributions to this project are welcome. Please ensure that you test your changes thoroughly and update the documentation accordingly.

## Authors

- Fernando Lucas Ruiz (Original Author)

## Acknowledgments

The simulations were carried out on dayhoff cluster. Thanks to the contributors of the GROMACS community for their valuable tools and support.

## Contact

For any inquiries, please reach out to by email fernando.lucas@um.es.
