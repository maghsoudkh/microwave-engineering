# Assignment 1: TE<sub>2,4</sub> mode analysis and modal filter in a rectangular waveguide

[Report (PDF)](report.pdf)

The waveguide has a = 108.0 mm, b = 83.1 mm, ε<sub>r</sub> = 3 and PEC walls.

1. The mode chart lists the cutoff frequency of every TE and TM mode up to TE<sub>2,4</sub>. TE<sub>1,0</sub> cuts off at 0.80 GHz and TE<sub>2,4</sub> at 4.46 GHz.
2. I plotted the closed-form E and H fields of TE<sub>2,4</sub> in MATLAB and compared them with a CST simulation of the fields, surface current and power flow. The cutoff frequency is 4.463 GHz in MATLAB and 4.459 GHz in CST.
3. I computed β, v<sub>p</sub>, v<sub>g</sub>, λ<sub>g</sub> and Z<sub>TE</sub> from 1.2 f<sub>c</sub> to 1.8 f<sub>c</sub>.
4. I computed the intermodal delay over 90 m for TE<sub>1,0</sub> against TE<sub>2,4</sub> and for TE<sub>1,4</sub> against TE<sub>2,4</sub>.
5. The modal filter uses a PEC wall at x = a/2 and a longitudinal slot at x = a/4. These two boundaries suppress every mode that cannot satisfy them, and TE<sub>2,4</sub> still propagates. A CST simulation confirms the design.

![TE2,4 fields in CST](figures/te24-fields-cst.png)
![Group velocity against frequency](figures/group-velocity.jpg)
![Slot of the modal filter](figures/modal-filter-slot.png)
