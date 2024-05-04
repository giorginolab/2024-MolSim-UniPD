PRELIMINARY SYLLABUS
====================

# Prerequisites

Some familiarity with the following.

*   The Unix (shell) environment
*   Google Colab
*   GitHub
*   Python programming
*   Chemical terminology
    

# Introduction to Molecular Dynamics and Force Fields

*   **Objective:** Introduce the basics of molecular dynamics simulations and the broad classes of force fields.
    
*   **Topics Covered:**
    *   Overview of molecular dynamics: principles, applications, and importance.
    *   Introduction to force fields: purpose, types, and their roles in simulations.
    *   We focus on explicit solvent, non-polarizable, all-atom models.
    *   Overview of state-of-the-art force fields: The CHARMM and Amber families.
    *   Discussion on the selection criteria for force fields in various research contexts.
        

# Pre-preparation of Molecular Systems

*   **Objective:** Understand how to prepare molecular systems for simulations, focusing on protein structures.
    
*   **Topics Covered:**
    *   Retrieving protein structures from the PDB: understanding orders of magnitude, sizes, and timescales.
    *   Protonation states: static vs dynamic considerations, optimizing hydrogen bond networks.
    *   Handling non-standard residues, unresolved atoms, and loops. Scanning the forcefield files.
    *   Decisions on water molecules, ions, metal centers, and non-peptide molecules.
        

# Building Molecular Systems for Simulations

*   **Objective:** Learn the steps involved in building a system for molecular dynamics simulations.
    
*   **Topics Covered:**
    *   Tools and techniques: tleap, psfgen, and OpenMM.
    *   Constructing the periodic box: considerations and best practices.
    *   Setting up a simulation: from biological assemblies to simulation-ready structures.
    *   Scanning forcefield files for supported non-standard residues, ions, and water models.
        

# Equilibration and Production Phases

*   **Objective:** Dive into the processes of equilibrating the system and running the production phase.
    
*   **Topics Covered:**
    *   Computing platforms
    *   The equilibration process: purpose, methods, and monitoring.
    *   Transitioning to the production phase: parameters, duration, and data collection.
    *   Biased vs unbiased simulations: Introduction to techniques like PLUMED and metadynamics.
    *   Free energy calculations. 
        

# Analysis and Interpretation of Simulation Data

*   **Objective:** Learn how to analyze simulation data and derive meaningful insights.
    
*   **Topics Covered:**
    *   Trajectory analysis techniques: wrapping, unwrapping, and alignment.
    *   Calculating diffusion coefficients and other relevant physical properties.
    *   Markov models
    *   Analyzing and interpreting simulation results: diffusion coefficients, 
        

# Advanced Topics in Molecular Dynamics

*   **Objective:** Explore advanced applications and techniques in molecular dynamics simulations.
    
*   **Topics Covered:**
    *   Membrane simulations: orientation, embedding, and lipid composition.
    *   Coarse-graining techniques: focus on the Martini force field.
    *   Biased vs unbiased simulations
        

# Docking and virtual screening

*   **Objective:** Learn the basics of how a virtual screening (given-target) campaign is made.
    
*   **Topics Covered:**
    *   Chemical formats for small molecules.
    *   Assignment of charges
    *   Flexibility and torsional search
    *   The AutoDock family: vina, smina, gnina
    *   Pitfalls: tautomers, protonation states, promiscuity…
        

# Software

*   OpenMM: [OpenMM](https://openmm.org/) 
*   Smina: [https://sourceforge.net/projects/smina/](https://sourceforge.net/projects/smina/) 
    

# Reading material

>  Giorgino T. [Analysis libraries for molecular trajectories: a cross-language synopsis](https://link.springer.com/protocol/10.1007/978-1-4939-9608-7_20). In: Bonomi M, Camilloni C, editors. [Biomolecular Simulations: Methods and Protocols](https://www.springer.com/it/book/9781493996070). Humana Press; 2019. p. 503–27. (Methods in Molecular Biology 2022). ISBN 978-1-4939-9608-7. [doi:10.1007/978-1-4939-9608-7\_20](https://doi.org/10.1007/978-1-4939-9608-7_20) available from [https://github.com/giorginolab/analysis\_libraries\_chapter](https://github.com/giorginolab/analysis_libraries_chapter) 
    

Each class includes theoretical explanations, practical demonstrations, and hands-on exercises using OpenMM and Python.








Day 1
=====

8/5/2024

Part 1-1 (morning)
------------------


Part 1-2 (afternoon)
------------------





Day 2
=====

15/5/2024



Part 2-1 (morning)
------------------



Part 2-2 (afternoon)
------------------


