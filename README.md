#Assignment of Cracking
###  1: Moment of Cracking
* **Problem:** Calculate the moment of cracking ($M_{cr}$) for a given concrete section.
* **Given:**
    * [cite_start]Size: $300 \text{ mm} \times 600 \text{ mm}$ [cite: 2, 3]
    * [cite_start]Concrete strength ($f_{ck}$): $25 \text{ MPa}$ [cite: 3]
* **Formulas Used:**
    * [cite_start]$M_{cr} = f_{cr} \frac{I}{y}$ [cite: 5]
    * [cite_start]Modulus of rupture ($f_{cr}$): $f_{cr} = 0.7\sqrt{f_{ck}}$ [cite: 8]
    * [cite_start]Moment of inertia ($I$): $I = \frac{BD^3}{12}$ [cite: 14]
    * [cite_start]Distance to the neutral axis ($y$): $y = \frac{D}{2}$ [cite: 13]
* **Calculations:**
    * [cite_start]$f_{cr} = 0.7 \times \sqrt{25} = 3.5 \text{ MPa}$ [cite: 11]
    * [cite_start]$y = \frac{600}{2} = 300 \text{ mm}$ [cite: 13]
    * [cite_start]$I = \frac{300 \times (600)^3}{12} = 5.4 \times 10^9 \text{ mm}^4$ [cite: 14]
    * [cite_start]$M_{cr} = \frac{(3.5 \times 10^3) \times (5.4 \times 10^9)}{300}$ [cite: 15, 16]
    * [cite_start]$M_{cr} = 6.3 \times 10^7 \text{ N-mm} = 63 \text{ kNm}$ [cite: 17, 18]

---

### 2: Service Level Moment and Bending Stress
* **Problem:** Calculate bending stress at 80% of the cracking moment.
* **Given:**
    * [cite_start]Cracking Moment: $M_{cr} = 63 \text{ kNm}$ [cite: 22, 32]
* **Calculations:**
* ### 3:
    * [cite_start]Moment at 80% of $M_{cr}$: $M = 0.80 \times 63 \text{ kNm} = 50.4 \text{ kNm}$ [cite: 33, 37]
    * [cite_start]Bending Stress ($\sigma$): $\sigma = \frac{My}{I}$ [cite: 38]
    * [cite_start]$\sigma = \frac{(50.4 \times 10^6) \times 300}{5.4 \times 10^9}$ [cite: 39]
    * [cite_start]$\sigma = 2.8 \text{ N/mm}^2$ [cite: 41]

---

###  4: Limiting Moment of Resistance ($M_{u,lim}$)
* **Problem:** Calculate the limiting moment of resistance for a given beam section.
* **Given:**
    * [cite_start]Concrete Grade: M20 [cite: 49]
    * [cite_start]Steel Grade: Fe-500 [cite: 47]
    * [cite_start]Beam width ($b$): $300 \text{ mm}$ [cite: 50]
    * [cite_start]Overall depth ($D$): $500 \text{ mm}$ [cite: 51]
    * [cite_start]Effective cover: $50 \text{ mm}$ [cite: 48]
* **Calculations:**
    * [cite_start]Effective depth ($d$): $d = D - \text{effective cover} = 500 - 50 = 450 \text{ mm}$ [cite: 52, 56]
    * [cite_start]Limiting depth of neutral axis ($x_{u,lim}$): $x_{u,lim} = 0.46 \times d = 0.46 \times 450 = 207 \text{ mm}$ [cite: 58, 59, 62]
    * Limiting Moment of Resistance ($M_{u,lim}$):
        * [cite_start]$M_{u,lim} = 0.36 f_{ck} b x_{u,lim} (d - 0.42 x_{u,lim})$ [cite: 61, 63, 64]
        * [cite_start]$M_{u,lim} = 0.36 \times 20 \times 300 \times 207 (450 - 0.42 \times 207)$ [cite: 66, 67, 68]
        * [cite_start]$M_{u,lim} = 162.22 \text{ kNm}$ [cite: 69]
    * **Alternative Method:**
        * [cite_start]For Fe-500 steel, $M_{u,lim} = 0.133 f_{ck} b d^2$ [cite: 71, 72]
        * [cite_start]$M_{u,lim} = 0.133 \times 20 \times 300 \times (450)^2$ [cite: 73]
        * [cite_start]$M_{u,lim} = 161.745 \times 10^6 \text{ N-mm} = 161.75 \text{ kNm}$ [cite: 74, 75]

---

###  5: Moment of Resistance for a Doubly Reinforced Section
* **Problem:** Calculate the ultimate moment of resistance for a doubly reinforced concrete section.
* **Given:**
    * Concrete: M20
    * Steel: Fe-500
    * Beam dimensions: $b = 300 \text{ mm}$, $D = 500 \text{ mm}$, Effective depth ($d$) = $450 \text{ mm}$
    * [cite_start]Tension reinforcement ($A_{st}$): 4 bars of 20 mm diameter [cite: 95]
    * [cite_start]Compression reinforcement ($A_{sc}$): 2 bars of 16 mm diameter [cite: 94]
* **Calculations:**
    * [cite_start]Area of compression steel ($A_{sc}$): $A_{sc} = 2 \times \frac{\pi}{4} \times 16^2 = 402.12 \text{ mm}^2$ [cite: 86, 93]
    * [cite_start]Area of tension steel ($A_{st}$): $A_{st} = 4 \times \frac{\pi}{4} \times 20^2 = 1256.64 \text{ mm}^2$ [cite: 96, 97]
    * [cite_start]Limiting moment of resistance ($M_{u,lim}$) is calculated as $162.22 \text{ kNm}$[cite: 112].
    * [cite_start]Limiting area of tension steel ($A_{st,lim}$): $A_{st,lim} = \frac{0.36 f_{ck} b x_{u,lim}}{0.87 f_y}$ [cite: 113, 115]
    * [cite_start]$A_{st,lim} = \frac{0.36 \times 20 \times 300 \times 207}{0.87 \times 500} = 1026.83 \text{ mm}^2$ [cite: 117, 118, 119]
    * [cite_start]Area of steel for additional moment ($A_{st2}$): $A_{st2} = A_{st} - A_{st,lim} = 1256.64 - 1026.83 = 229.81 \text{ mm}^2$ [cite: 120]
    * [cite_start]Strain in compression steel ($\epsilon_{sc}$): $\epsilon_{sc} = 0.0035 (1 - \frac{d_c}{x_{u,lim}}) = 0.0035 (1 - \frac{50}{207}) = 0.00265$ [cite: 123, 125]
    * [cite_start]Stress in compression steel ($f_{sc}$): $f_{sc} = 412 \text{ N/mm}^2$ (from stress-strain curve) [cite: 130]
    * [cite_start]Moment of resistance from compression steel ($M_{u2}$): $M_{u2} = f_{sc} A_{sc} (d - d_c)$ [cite: 131]
    * [cite_start]$M_{u2} = 412 \times 402.12 (450 - 50) = 66.21 \times 10^6 \text{ N-mm} = 66.21 \text{ kNm}$ [cite: 132, 133]
    * [cite_start]Total ultimate moment of resistance ($M_u$): $M_u = M_{u,lim} + M_{u2}$ [cite: 135]
    * [cite_start]$M_u = 162.22 + 66.21 = 228.43 \text{ kNm}$ [cite: 135]
