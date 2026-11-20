# Microwave devices: waveguides, couplers and matching networks

Homework from the Microwave Devices course, M.Sc. in Electronic Engineering, University of Padova, academic year 2025/2026.

Each assignment starts from an analytical design, models it in MATLAB and, where the geometry allows, checks it with a full-wave simulation in CST Studio Suite. The README in each folder compares the results of the different methods.

| Assignment | Topic | Main results |
|---|---|---|
| [1](rectangular-waveguide/) | Rectangular waveguide with ε<sub>r</sub> = 3, TE<sub>2,4</sub> mode | Cutoff frequencies of 23 modes. TE<sub>2,4</sub> cuts off at 4.463 GHz in MATLAB and 4.459 GHz in CST, less than 0.1 % apart. Dispersion, intermodal delay and a modal filter built from a PEC wall and a slot. |
| [2](branchline-coupler/) | Unequal-split branch-line coupler in microstrip, f<sub>0</sub> = 1.29 GHz, 80 Ω ports | Even/odd-mode ABCD analysis gives Z<sub>01</sub> = 154.4 Ω and Z<sub>02</sub> = 71.0 Ω. Hammerstad synthesis, MATLAB S-parameters, a ±5 % tolerance study and a CST check. |
| [4](impedance-matching/) | Matching 533 Ω to 50 Ω at 1.953 GHz | Two single-stub solutions, two lumped L-section solutions, and 3- and 4-section binomial transformers, compared by bandwidth at Γ<sub>m</sub> < 0.025. |

## Methods used

- Modal analysis of waveguides: field and surface-current distributions, dispersion and group delay.
- Design of passive microwave circuits: branch-line couplers, stubs, lumped L-networks and multisection quarter-wave transformers.
- Network analysis with ABCD and S-parameters, including even/odd-mode decomposition.
- MATLAB models, CST full-wave simulation and Monte Carlo tolerance analysis.

Each folder has the report PDF, its LaTeX source in `latex/` and the main figures.

Author: Amirkhashayar Maghsoud

## License

The reports, their LaTeX sources, the figures and the text are licensed under [CC BY 4.0](LICENSE). You may reuse them with credit to the author.
