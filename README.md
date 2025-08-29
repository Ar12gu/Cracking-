###Assignment
1. Determine the cracking moment of the beam section having a size of 600 mm (Depth) × 300 mm (Width), made up of plain cement concrete. Assume the concrete is of grade 25 MPa.

2.Find corresponding moment at service level, by making use of reduction factor of 0.67 and partial safety factor for the concrete.

3.Compute the bending stress in the extreme fibre of the beam section for any assumed bending moment of 80% of the cracking moment.

4.Find maximum factored moment which this section can carry for Fe-500 rebars, when section is singly reinforced. Use effective cover of 50 mm.

5.Find maximum factored moment which this section can carry for Fe-500 rebars, when section is doubly reinforced. Use effective cover of 50 mm for tension and compression.
##Solution

Solution:

### 1. Cracking Moment of a Plain Concrete Beam

The cracking moment ($M_{cr}$) is the bending moment that causes the first crack to form in the concrete beam. It is calculated using the elastic flexure formula for an uncracked section.

* **Modulus of Rupture ($f_r$)**: This represents the tensile strength of the concrete. For M25 concrete, it's calculated as $f_r = 0.7\sqrt{f_{ck}}$.
    $f_r = 0.7\sqrt{25 \text{ MPa}} = 3.5 \text{ MPa}$
* **Gross Moment of Inertia ($I_{gross}$)**: For a rectangular section, it's $I_{gross} = \frac{bd^3}{12}$.
    $I_{gross} = \frac{300 \text{ mm} \times (600 \text{ mm})^3}{12} = 5.4 \times 10^9 \text{ mm}^4$
* **Distance to Extreme Fiber ($y_t$)**: For a symmetric rectangular section, it is half the depth.
    $y_t = \frac{600 \text{ mm}}{2} = 300 \text{ mm}$
* **Cracking Moment ($M_{cr}$)**:
    $M_{cr} = \frac{f_r \times I_{gross}}{y_t} = \frac{3.5 \text{ MPa} \times 5.4 \times 10^9 \text{ mm}^4}{300 \text{ mm}} = 63 \times 10^6 \text{ N-mm} = 63.0 \text{ kN-m}$

The cracking moment is **63.0 kN·m**.

***

### 2. Moment at Service Level

The service level moment is found by applying a reduction factor of 0.67 and a partial safety factor for concrete ($\gamma_c$) of 1.5.

$M_{service} = \frac{M_{cr} \times \text{Reduction Factor}}{\gamma_c} = \frac{63.0 \text{ kN-m} \times 0.67}{1.5} = 28.14 \text{ kN-m}$

The corresponding moment at the service level is **28.14 kN·m**.

***

### 3. Bending Stress in the Extreme Fiber

The bending stress ($\sigma$) at any moment ($M$) is calculated using the formula $\sigma = \frac{My}{I_{gross}}$. We will use a moment equal to 80% of the cracking moment.

* **Assumed Moment ($M$)**: $0.80 \times 63.0 \text{ kN-m} = 50.4 \text{ kN-m}$
* **Bending Stress ($\sigma$)**:
    $\sigma = \frac{(50.4 \times 10^6 \text{ N-mm}) \times 300 \text{ mm}}{5.4 \times 10^9 \text{ mm}^4} = 2.8 \text{ MPa}$

The bending stress is **2.8 MPa**.

***

### 4. Maximum Factored Moment (Singly Reinforced)

This calculation determines the ultimate moment capacity of the section when reinforced with tension steel only.

* **Effective Depth ($d_{eff}$)**: $d_{eff} = 600 \text{ mm} - 50 \text{ mm} = 550 \text{ mm}$
* **Limiting Neutral Axis Depth ($x_{u,lim}$)**: For Fe-500 steel, the limiting neutral axis depth is $0.46d_{eff}$ to ensure a ductile failure.
    $x_{u,lim} = 0.46 \times 550 \text{ mm} = 253 \text{ mm}$
* **Limiting Moment of Resistance ($M_{u,lim}$)**:
    $M_{u,lim} = 0.36 \times f_{ck} \times b \times x_{u,lim} \times (d_{eff} - 0.42x_{u,lim})$
    $M_{u,lim} = 0.36 \times 25 \times 300 \times 253 \times (550 - 0.42 \times 253) = 303.12 \times 10^6 \text{ N-mm} = 303.12 \text{ kN-m}$

The maximum factored moment the singly reinforced section can carry is **303.12 kN·m**.

***

### 5. Maximum Factored Moment (Doubly Reinforced)

To compute the moment for a **doubly reinforced section**, the **area of compression steel ($A_{sc}$) must be provided**. Without this value, a numerical solution is impossible.

The formula is:
$M_u = M_{u,lim} + M_{u2}$
where $M_{u2} = A_{sc}(f_{sc} - 0.446f_{ck})(d_{eff} - d')$

$M_{u,lim}$ is the same as calculated above. The additional moment capacity, $M_{u2}$, depends on the area of steel in the compression zone, which is not given.
#thank you
