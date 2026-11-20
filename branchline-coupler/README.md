# Assignment 2: unequal-split branch-line coupler in microstrip

[Report (PDF)](report.pdf)

The specification is f<sub>0</sub> = 1290 MHz, port impedance Z<sub>0</sub> = 80 Ω and k = 4.6, on a substrate with ε<sub>r</sub> = 3.5 and h = 2.9 mm.

1. The analytical design uses even/odd-mode excitation and ABCD matrices. Setting S<sub>44</sub> = S<sub>41</sub> = 0 gives 1/z<sub>02</sub>² − 1/z<sub>01</sub>² = 1, which leads to Z<sub>01</sub> = 154.4 Ω, Z<sub>02</sub> = 71.0 Ω and the closed-form S-matrix.
2. Hammerstad's formulas give the microstrip dimensions:

   | Line | Z [Ω] | w [mm] | ε<sub>eff</sub> | λ/4 [mm] |
   |---|---|---|---|---|
   | Z<sub>01</sub> | 154.42 | 0.42 | 2.45 | 37.1 |
   | Z<sub>02</sub> | 71.03 | 3.55 | 2.63 | 35.8 |

3. MATLAB computes the S-parameters from the cascaded ABCD model.
4. A Monte Carlo run with 20 samples varies Z<sub>01</sub> and Z<sub>02</sub> randomly by ±5 %.
5. A full-wave CST simulation of the microstrip layout checks the design.

![CST layout](figures/cst-layout.png)
![S-parameters from CST](figures/cst-s-parameters.png)
![S41 with ±5 % tolerance](figures/s41-tolerance.jpg)
