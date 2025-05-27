# SSVEP SNR Computation

Author: **Jules GOMEL**  
Year: **2025**


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15525420.svg)](https://doi.org/10.5281/zenodo.15525420)

## Overview

This repository contains code to practice SSVEP (Steady-State Visually Evoked Potential) signal-to-noise ratio (SNR) computation based on EEG data from **Ladouce et al. (2022)**:

> *Improving user experience of SSVEP BCI through low amplitude depth and high frequency stimuli design*  
> [Zenodo Dataset](https://zenodo.org/record/5907009)

The SNR computation methodology follows the approach proposed by **Cohen & Gulbinaite (2017)**:

> *Rhythmic Entrainment Source Separation: Optimizing analyses of neural responses to rhythmic sensory stimulation*  
> [Paper Link (DOI)](https://doi.org/10.1016/j.neuroimage.2017.04.015)

## Method

The signal-to-noise ratio (SNR) is calculated by comparing the power at a target frequency to the average power of neighboring frequencies, excluding a small band around the target to avoid signal contamination. This method is particularly useful for analyzing rhythmic entrainment in EEG/BCI studies.

## Requirements

- Python 3.x
- NumPy
- SciPy
- Matplotlib (optional for plotting)
- MNE (optional if working directly with EEG files)

### TO DO

- Requirements
- environment file in yaml
