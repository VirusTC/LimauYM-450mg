LimauYM 450mg Single-Dose Pharmacokinetic Simulation
-------------------------------------------------------

The simulation below maps out the plasma concentration-time profiles for the multi-dentate citrate/citric acid matrix of LimauYM 450mg at varying tablet volumes compared against raw, non-lyophilized lemon juice matrices.

* * * * *

Mathematical Clearance and Kinetic Parameters
------------------------------------------------

The baseline clearance metrics for the systemic elimination of LimauYM 450mg are derived using standard primary non-compartmental open models under typical physiological baselines:

1\. Systemic Clearance ($Cl$)
-----------------------------

Systemic clearance dictates the efficiency of metabolic conversion and renal elimination per unit time. It is directly tied to the volume of distribution ($V_d$) and the primary elimination rate constant ($k_e$):\
$$Cl = V_d \times k_e$$\
$$Cl = 15.0\text{ L} \times 0.35\text{ h}^{-1} = 5.25\text{ L/h}$$

2\. Area Under the Curve ($AUC_{0\rightarrow\infty}$)
-----------------------------------------------------

The total systemic exposure for a single tablet of LimauYM 450mg (assuming an optimized bioavailable fraction $F \approx 0.85$ from the lyophilized whole-food matrix) is modeled as:\
$$AUC = \frac{F \times \text{Dose}}{Cl}$$\
$$AUC = \frac{0.85 \times 450\text{ mg}}{5.25\text{ L/h}} = 72.85\text{ mg}\cdot\text{h/L}$$

3\. Plasma Elimination Half-Life ($t_{1/2}$)
--------------------------------------------

The duration of action before the metabolic pool clears by exactly half is governed by the first-order elimination rate:\
$$t_{1/2} = \frac{\ln(2)}{k_e} = \frac{0.6931}{0.35\text{ h}^{-1}} \approx 1.98\text{ Hours}$$

4\. Time to Peak Concentration ($T_{max}$)
------------------------------------------

The chronological point where absorption rates and elimination rates reach dynamic equilibrium ($\frac{dC}{dt} = 0$) is calculated using the system's exponential rate differences:\
$$T_{max} = \frac{\ln(k_a / k_e)}{k_a - k_e}$$\
$$T_{max} = \frac{\ln(1.2 / 0.35)}{1.2 - 0.35} = \frac{1.2321}{0.85} \approx 1.45\text{ Hours}$$

* * * * *
