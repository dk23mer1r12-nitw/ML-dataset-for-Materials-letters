# ML-dataset-for-Materials-letters
ML dataset (Material letters)

README Template (FAIR-Compliant)
**Overview**
This repository contains experimental mechanical testing data for Triply Periodic Minimal Surface (TPMS) lattice structures used in biomedical scaffolds and lightweight implants.
Four configurations are included:

Lidinoid 40% porosity

Lidinoid 50% porosity

FCC (Face-Centred Cubic) lattice 40% porosity

FCC 50% porosity

The dataset includes load-displacement and stress–strain measurements obtained from quasi-static compression tests. Contents
List and briefly describe each file and folder.

This study investigates three distinct lattice geometries, body centred cubic (BCC), face centred cubic (FCC), and lidinoid (a TPMS-based) each fabricated at 40% and 50% porosity using a fused deposition modelling (FDM) 3D printing process with polylactic acid (PLA) as the base material. The printed samples are underwent to uniaxial compression testing using universal tensile machine (UTM) to assess the mechanical performance, particularly focusing on elastic modulus, energy absorption and stress distribution characteristics. The experimental data were carefully curated and optimized to train machine learning models for predicting elastic modulus from structural features. These models employed data-driven techniques to boost accuracy and reduce residual errors, resulting in improved predictive reliability. The ML predicted values were then compared against the experimentally measured result, showing that strong agreement and validating the efficient of the predictive framework

**Data Description**
load-displacement and stress-strain curve, Load (kN), displacement(mm), Stress (MPa) and strain (mm/mm).CSV, Supervised machine learning algorithms are used in this study.

**Methods**
The data was taken from an experimental compressive test using a UTM machine and processed for Machine learning prediction.


**License**
The Python scripts, Jupyter Notebooks, and associated code files used in this work are released under the MIT License, which permits free reuse, modification, distribution, and integration in other projects, provided that proper credit is given to the author.

**Citation**
Provide the dataset citation, including DOI.
