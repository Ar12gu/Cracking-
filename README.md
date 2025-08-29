###Assignment
1. Determine the cracking moment of the beam section having a size of 600 mm (Depth) × 300 mm (Width), made up of plain cement concrete. Assume the concrete is of grade 25 MPa.

2.Find corresponding moment at service level, by making use of reduction factor of 0.67 and partial safety factor for the concrete.

3.Compute the bending stress in the extreme fibre of the beam section for any assumed bending moment of 80% of the cracking moment.

4.Find maximum factored moment which this section can carry for Fe-500 rebars, when section is singly reinforced. Use effective cover of 50 mm.

5.Find maximum factored moment which this section can carry for Fe-500 rebars, when section is doubly reinforced. Use effective cover of 50 mm for tension and compression.
##Solution

### Moment of Cracking
[cite_start]The cracking moment ($M_{cr}$) is calculated for a concrete section measuring $300 \text{ mm} \times 600 \text{ mm}$ [cite: 3] [cite_start]with a concrete strength ($f_{ck}$) of $25 \text{ MPa}$[cite: 3].
* [cite_start]**Modulus of rupture ($f_{cr}$)**: The modulus of rupture is calculated as $f_{cr} = 0.7\sqrt{f_{ck}}$[cite: 8]. [cite_start]$f_{cr} = 0.7 \times \sqrt{25} = 3.5 \text{ MPa}$[cite: 11].
* [cite_start]**Moment of inertia ($I$)**: The moment of inertia for the beam section is calculated using $I = \frac{BD^3}{12}$[cite: 14]. [cite_start]$I = \frac{300 \times (600)^3}{12} = 5.4 \times 10^9 \text{ mm}^4$[cite: 14].
* [cite_start]**Distance to neutral axis ($y$)**: The distance from the neutral axis to the extreme fiber is $y = \frac{D}{2} = \frac{600}{2} = 300 \text{ mm}$[cite: 13].
* [cite_start]**Cracking Moment ($M_{cr}$)**: The cracking moment is found using the formula $M_{cr} = \frac{f_{cr} I}{y}$[cite: 5, 7]. [cite_start]$M_{cr} = \frac{(3.5 \times 10^3) \times (5.4 \times 10^9)}{300}$[cite: 15, 16]. [cite_start]The result is $M_{cr} = 6.3 \times 10^7 \text{ N-mm}$ [cite: 17][cite_start], which is equal to $63 \text{ kNm}$[cite: 18].

***

### Service Level Moment and Bending Stress
[cite_start]The bending stress ($\sigma$) is calculated at 80% of the cracking moment[cite: 29].
* [cite_start]**Moment ($M$)**: The moment is calculated as $80\%$ of the cracking moment, which is $63 \text{ kNm}$[cite: 32]. [cite_start]The calculated value is $M = 50.4 \text{ kNm}$[cite: 37].
* [cite_start]**Bending Stress ($\sigma$)**: The bending stress is calculated using the formula $\sigma = \frac{My}{I}$[cite: 38]. [cite_start]$\sigma = \frac{(50.4 \times 10^6 \text{ N-mm}) \times 300 \text{ mm}}{5.4 \times 10^9 \text{ mm}^4}$[cite: 39, 40].
* [cite_start]**Result**: The bending stress is $2.8 \text{ N/mm}^2$[cite: 41].

***

### Limiting Moment of Resistance ($M_{u,lim}$)
[cite_start]The limiting moment of resistance is calculated for a beam with Fe-500 steel grade [cite: 47][cite_start], M20 concrete [cite: 49][cite_start], a width of $300 \text{ mm}$ [cite: 50][cite_start], an overall depth of $500 \text{ mm}$ [cite: 51][cite_start], and an effective cover of $50 \text{ mm}$[cite: 48].
* [cite_start]**Effective depth ($d$)**: The effective depth is calculated as the overall depth minus the effective cover[cite: 52]. [cite_start]$d = 500 - 50 = 450 \text{ mm}$[cite: 56].
* [cite_start]**Limiting neutral axis depth ($x_{u,lim}$)**: The limiting depth is given by $x_{u,lim} = 0.46 \times d$[cite: 58]. [cite_start]$x_{u,lim} = 0.46 \times 450 = 207 \text{ mm}$[cite: 62].
* [cite_start]**Limiting Moment ($M_{u,lim}$)**: The limiting moment is calculated using the formula $M_{u,lim} = 0.36 f_{ck} b x_{u,lim} (d - 0.42 x_{u,lim})$[cite: 64].
    * [cite_start]$M_{u,lim} = 0.36 \times 20 \times 300 \times 207 (450 - 0.42 \times 207)$[cite: 66, 67, 68].
    * [cite_start]The result is $162.22 \text{ kNm}$[cite: 69].
* [cite_start]**Alternative Calculation**: An alternative formula for Fe-500 steel is $M_{u,lim} = 0.133 f_{ck} b d^2$[cite: 72].
    * [cite_start]$M_{u,lim} = 0.133 \times 20 \times 300 \times (450)^2$[cite: 73].
    * [cite_start]The result is $161.745 \times 10^6 \text{ N-mm}$, which is $161.75 \text{ kNm}$[cite: 74, 75].

***

### Ultimate Moment of Resistance for a Doubly Reinforced Section
[cite_start]The ultimate moment of resistance is calculated for a doubly reinforced section with M20 concrete [cite: 82][cite_start], Fe-500 steel [cite: 85][cite_start], a width of $300 \text{ mm}$, a depth of $500 \text{ mm}$, and an effective depth of $450 \text{ mm}$[cite: 82].
* **Area of steel**:
    * [cite_start]Compression steel ($A_{sc}$): 2 bars of 16 mm diameter[cite: 94]. [cite_start]$A_{sc} = 2 \times \frac{\pi}{4} \times (16)^2 = 402.12 \text{ mm}^2$[cite: 93].
    * [cite_start]Tension steel ($A_{st}$): 4 bars of 20 mm diameter[cite: 95]. [cite_start]$A_{st} = 4 \times \frac{\pi}{4} \times (20)^2 = 1256.64 \text{ mm}^2$[cite: 97].
* **Limiting Area of Tension Steel ($A_{st,lim}$)**: This is the area of steel required to resist the limiting moment.
    * [cite_start]Formula: $A_{st,lim} = \frac{0.36 f_{ck} b x_{u,lim}}{0.87 f_y}$[cite: 113, 115].
    * [cite_start]Calculation: $A_{st,lim} = \frac{0.36 \times 20 \times 300 \times 207}{0.87 \times 500} = 1026.83 \text{ mm}^2$[cite: 117, 118, 119].
* [cite_start]**Area of steel for additional moment ($A_{st2}$)**: $A_{st2} = A_{st} - A_{st,lim} = 1256.64 - 1026.83 = 229.81 \text{ mm}^2$[cite: 120].
* **Stress in compression steel ($f_{sc}$)**:
    * [cite_start]Strain ($\epsilon_{sc}$): $\epsilon_{sc} = 0.0035 (1 - \frac{d_c}{x_{u,lim}}) = 0.0035 (1 - \frac{50}{207}) = 0.00265$[cite: 123, 125].
    * [cite_start]Stress: For the calculated strain, the stress from the stress-strain curve is $f_{sc} = 412 \text{ N/mm}^2$[cite: 130].
* **Moment from compression steel ($M_{u2}$)**:
    * [cite_start]Formula: $M_{u2} = f_{sc} A_{sc} (d - d_c)$[cite: 131].
    * [cite_start]Calculation: $M_{u2} = 412 \times 402.12 (450 - 50) = 66.21 \times 10^6 \text{ N-mm}$[cite: 132].
    * [cite_start]Result: $M_{u2} = 66.21 \text{ kNm}$[cite: 133].
* **Total Ultimate Moment ($M_u$)**:
    * [cite_start]Formula: $M_u = M_{u,lim} + M_{u2}$[cite: 135].
    * [cite_start]Calculation: $M_u = 162.22 + 66.21 = 228.43 \text{ kNm}$[cite: 135].
