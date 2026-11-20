# HW2 — Unequal-Split Branch-Line Coupler in Microstrip

[Report (PDF)](report.pdf)

**Specifications:** f<sub>0</sub> = 1290 MHz, port impedance Z<sub>0</sub> = 80 Ω, k = 4.6, substrate ε<sub>r</sub> = 3.5, h = 2.9 mm.

1. **Analytical design:** even/odd-mode excitation and ABCD matrices. Imposing S<sub>44</sub> = S<sub>41</sub> = 0 gives the condition 1/z<sub>02</sub>² − 1/z<sub>01</sub>² = 1, which leads to **Z<sub>01</sub> = 154.4 Ω** and **Z<sub>02</sub> = 71.0 Ω**, plus the closed-form S-matrix.
2. **Microstrip synthesis (Hammerstad):**

   | Line | Z [Ω] | w [mm] | ε<sub>eff</sub> | λ/4 [mm] |
   |---|---|---|---|---|
   | Z<sub>01</sub> | 154.42 | 0.42 | 2.45 | 37.1 |
   | Z<sub>02</sub> | 71.03 | 3.55 | 2.63 | 35.8 |

3. **MATLAB S-parameters:** computed from the cascaded ABCD model.
4. **Tolerance study:** Monte Carlo with ±5 % random variation of Z<sub>01</sub> and Z<sub>02</sub> (20 samples).
5. **CST full-wave simulation** of the microstrip layout.

![CST layout](figures/cst-layout.png)
![CST S-parameters](figures/cst-s-parameters.png)
![S41 with ±5% tolerance](figures/s41-tolerance.jpg)
