# Semi-Implicit and Exponential Mid-Point Integrators for Particle Dynamics

## Description
This repository contains Python implementations of **$\epsilon$-implicit** and **exponential mid-point integrators** for simulating the motion of particles under gravitational forces with drag and stochastic gas interactions. These integrators are particularly useful for **stiff systems**, providing stable and efficient time evolution compared to purely explicit methods.

## Key features:
- **Semi-implicit integration (IMEX):** Combines explicit and implicit updates for stable handling of stiff terms.
- **Exponential mid-point integrator:** Uses exponential updates to accurately model damping or drag forces.
- **$\epsilon$-implicit method:** Updates stiff components of a system implicitly while treating non-stiff components explicitly, improving stability without the full computational cost of a fully implicit method.
- Particle dynamics under central gravitational forces.
- Interaction with a background gas through stochastic velocities.
- Simple Python implementation suitable for modification and extension.

## References
1. Hairer, E., Nørsett, S. P., & Wanner, G. (1993). *Solving Ordinary Differential Equations I: Nonstiff Problems*. Springer.  
2. Hochbruck, M., & Ostermann, A. (2010). *Exponential Integrators*. Acta Numerica, 19, 209–286.  
3. Leimkuhler, B., & Reich, S. (2004). *Simulating Hamiltonian Dynamics*. Cambridge University Press.  
4. Ascher, U. M., Ruuth, S. J., & Spiteri, R. J. (1997). *Implicit-Explicit Runge-Kutta Methods for Time-Dependent PDEs*. Applied Numerical Mathematics, 25(2-3), 151–167.
