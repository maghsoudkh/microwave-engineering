# HW1 — Rectangular Waveguide: TE<sub>2,4</sub> Mode Analysis and Modal Filter

[Report (PDF)](report.pdf)

**Structure:** a = 108.0 mm, b = 83.1 mm, ε<sub>r</sub> = 3, PEC walls.

1. **Mode chart:** cutoff frequencies of all TE/TM modes up to TE<sub>2,4</sub>. TE<sub>1,0</sub> cuts off at 0.80 GHz and TE<sub>2,4</sub> at 4.46 GHz.
2. **Fields:** closed-form E and H for TE<sub>2,4</sub>, plotted in MATLAB and simulated in CST, including the surface current density and power flow. f<sub>c</sub> is 4.463 GHz in MATLAB and 4.459 GHz in CST.
3. **Dispersion (1.2 f<sub>c</sub> to 1.8 f<sub>c</sub>):** β, v<sub>p</sub>, v<sub>g</sub>, λ<sub>g</sub> and Z<sub>TE</sub> against frequency.
4. **Intermodal dispersion:** group-delay difference over 90 m, TE<sub>1,0</sub> vs TE<sub>2,4</sub> and TE<sub>1,4</sub> vs TE<sub>2,4</sub>.
5. **Modal filter:** a PEC wall at x = a/2 and a longitudinal slot at x = a/4. They remove the modes that are incompatible with these boundary conditions and keep TE<sub>2,4</sub>. The design was checked in CST.

![TE24 fields in CST](figures/te24-fields-cst.png)
![Group velocity](figures/group-velocity.jpg)
![Modal filter slot](figures/modal-filter-slot.png)
