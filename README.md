# All-Optical-NOT-Gate-Silicon-Ring-Resonator-
# All-Optical NOT Gate using Silicon Ring Resonator

## Abstract
This project demonstrates the design and simulation of an all-optical NOT logic gate using a polarization-conversion mechanism in a single silicon micro-ring resonator. The device operates based on the nature of the pump signal, rather than intensity, achieving polarization conversion with a response time of 0.2 ps. Finite-Difference Time-Domain (FDTD) simulations were performed using Ansys Lumerical to validate the design's efficiency and speed.

## Implementation
- Designed a race-track silicon ring resonator with optimized geometric parameters.
- Material properties were defined for the silicon waveguide and silicon dioxide substrate.
- Configured quasi-TE polarized input source and pump signals.
- FDTD simulation setup included field and time monitors to observe light propagation.
- Extracted transmission spectrum and polarization conversion characteristics.
- Verified logical inversion behavior (NOT gate functionality) via polarization state changes.

## Results
- Achieved polarization conversion from quasi-TE (Logic 1) to quasi-TM (Logic 0) with high efficiency.
- Response time of ~0.2 ps.
- Q-factor and signal spectrum validated through simulations.
- Simulation results matched the expected NOT gate truth table functionality.
  
## Conclusion
The proposed polarization-conversion-based all-optical NOT gate demonstrates ultra-fast operation with a simple and compact design. Its compatibility with silicon-on-insulator platforms makes it highly suitable for integration into photonic circuits, paving the way for future optical computing applications.

## Files Included
- **ESA_PROJECT.fsp** — Lumerical FDTD Simulation File.
- **Project Report (PDF)** — Complete documentation.
- **Simulation Diagrams & Results** — Visual outputs of the simulated logic gate.

## References
- Bharti, G. K., Singh, M. P., & Rakshit, J. K. (2019). "Design and Modeling of Polarization-Conversion Based All-Optical Logic Gates." *Silicon*, 12(6), 1279–1288.
- Kumar, A., Kumar, S., & Raghuvanshi, S. K. (2014). "Implementation of XOR/XNOR and AND Logic Gates Using Mach-Zehnder Interferometers." *Optik*, 125(19), 5764–5767.
