# Microwave Devices — Waveguides, Couplers and Matching Networks

Homework portfolio from the **Microwave Devices** course, M.Sc. in Electronic Engineering, Università degli Studi di Padova (A.Y. 2025/2026).

Each assignment combines **analytical design**, **MATLAB modelling** and, where relevant, **full-wave EM simulation in CST Studio Suite**. Results from the different methods are cross-checked against each other.

| HW | Topic | Highlights |
|---|---|---|
| [1](rectangular-waveguide/) | Rectangular waveguide (ε<sub>r</sub> = 3), TE<sub>2,4</sub> mode | Cutoff of 23 modes; TE<sub>2,4</sub> f<sub>c</sub> = 4.463 GHz (MATLAB) vs 4.459 GHz (CST), < 0.1 % apart; dispersion and intermodal delay; **modal-filter design** with a PEC wall and slot |
| [2](branchline-coupler/) | Unequal-split branch-line coupler in microstrip (f<sub>0</sub> = 1.29 GHz, 80 Ω ports) | Even/odd-mode ABCD derivation of Z<sub>01</sub> = 154.4 Ω and Z<sub>02</sub> = 71.0 Ω; Hammerstad synthesis; MATLAB S-parameters; ±5 % tolerance Monte Carlo; CST verification |
| [4](impedance-matching/) | Matching 533 Ω to 50 Ω at 1.953 GHz | Single-stub (2 solutions), L-section lumped (2 solutions), 3- and 4-section binomial transformers; bandwidth comparison at Γ<sub>m</sub> < 0.025 |

## Skills demonstrated

- Electromagnetic field theory: modal analysis, field and surface-current distributions, dispersion, group delay.
- Passive microwave circuit design: couplers, stubs, lumped L-networks, multisection quarter-wave transformers.
- Network analysis: ABCD and S-parameters, even/odd-mode decomposition.
- Tools: MATLAB modelling, CST Studio Suite full-wave simulation, and tolerance (Monte Carlo) analysis.

Each folder contains the report PDF, its LaTeX source (`latex/`) and the key figures.

**Author:** Amirkhashayar Maghsoud
