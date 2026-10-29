# Helmholtz Resonator — Experimental Acoustics

**Status:** documentation in progress  
**Context:** CPGE MPI TIPE  
**Topics:** acoustics, resonance, harmonic oscillator, signal processing

## Overview

This project investigates the resonance of a Helmholtz resonator: a cavity connected to the outside through a narrow opening. The air in the neck can be approximated as an oscillating mass, while the compressibility of the air in the cavity provides a restoring effect.

The objective is to compare experimental resonance measurements with a simplified physical model.

## Experimental setup

- Signal generator (GBF) and loudspeaker
- Microphone and oscilloscope
- Resonators with different cavity volumes and neck geometries
- Frequency sweeps and time-domain signal recordings

## Method

1. Excite the resonator over a range of frequencies.
2. Record the measured response.
3. Plot the response as a function of frequency and identify the resonance peak.
4. Analyse time-domain signals and, where appropriate, their frequency spectrum.
5. Compare measurements with the model and discuss uncertainty and assumptions.

## Model

A simplified Helmholtz-resonator model gives the approximate resonance frequency

\[
f_0 = \frac{c}{2\pi}\sqrt{\frac{S}{V L_{\mathrm{eff}}}},
\]

where:

- \(c\) is the speed of sound,
- \(S\) is the neck cross-sectional area,
- \(V\) is the cavity volume,
- \(L_{\mathrm{eff}}\) is the effective neck length, including end corrections.

This model assumes a compact cavity, small oscillations and an appropriate approximation of the neck air as a lumped mass. Real measurements can differ because of losses, geometry, coupling to the loudspeaker and microphone, and uncertainty in effective length.

## Analysis tools

- Python
- NumPy
- Matplotlib
- SciPy

## Repository structure

```text
helmholtz-resonator/
├── data/          # Add measurement files here (CSV)
├── notebooks/     # Optional exploratory analysis
├── src/           # Reusable analysis scripts
├── figures/       # Exported plots
└── README.md
```

## Reproducibility checklist

- [ ] Add anonymised/raw measurement CSV files and describe their columns.
- [ ] Add the final analysis script or notebook.
- [ ] Include plots with units, legends and measurement conditions.
- [ ] Explain how resonance frequency and bandwidth are extracted.
- [ ] Report uncertainty and distinguish measured results from theoretical estimates.
- [ ] Add references used in the project.

## Note

This repository is a presentation template. Add only data, plots and conclusions that you are permitted to publish, and verify every reported numerical value against the final analysis.
