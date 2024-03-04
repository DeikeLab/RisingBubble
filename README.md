# RisingBubble
#### Simulation files 
bubble.c

#### Comparison with Loth (2008)
The DNS results of bubble rising in the quiescent medium are compared with experiments in Loth 2008. 
As the dimensional analysis shows, three dimensionless variables are needed to describe this problem. To compare, we use the same dimensionless variables as in the experiment of Loth 2008, the drag coefficient $C_d = {4dg}/{3w_b^2}$, the quiescent bubble Reynolds number $Re_q = {\rho_l w_b d}/{\mu_l}$, and the Morton number ${Mo} = {g\mu_l^4}/{\rho_l\sigma^3}$,
which lacks a direct physical interpretation but is conveniently used to characterize liquid properties in experiments. The figure below shows that the DNS results are in good agreement with the fitting for clean spherical bubbles
$$C_d =\frac{16}{Re_q}\left\{1\right\}$$
and implicit semiempirical formula for deformed bubbles at different Morton numbers

![Comparison](https://github.com/DeikeLab/RisingBubble/blob/main/Comparison.png)

#### Grid convergence 
Velocity signal of bubble rising from simulations with different resolutions (L8/L9/L10). Results are converged between L9 and L10, therefore L9 is enough.

+ Quiescent case:

![Convergence](https://github.com/DeikeLab/RisingBubble/blob/main/VelSignal.png)

+ Turbulent case:

![Convergence](https://github.com/DeikeLab/RisingBubble/blob/main/VelSignalt.png)
