Research topics in the group

.. contents:: Table of Contents
   :depth: 1

Ab-initio Quantum Monte Carlo simulations
---------------------------------------------------------------------

The Schrödinger equation provides insight into the behavior of "electrons" that govern the chemical and physical properties of materials. To solve this equation numerically, first-principles calculations are typically employed, with the wavefunction theory (WFT) or density functional theory (DFT) being the most popular approaches in material science and condensed matter physics. However, these methods still have serious drawbacks, such as the significant influence of the exchange-correlation functional in DFT calculations, which can lead to inaccurate predictions.

Quantum Monte Carlo (QMC) is a promising alternative that offers a stochastic approach to solving the many-body Schrödinger equation, enabling the direct handling of a many-body wave function without reliance on exchange-correlation functionals. This approach is poised to become the next generation of electronic structure calculations, particularly with the advent of large parallel computers in the 21st century, which have greatly reduced the statistical error problem associated with the Monte Carlo method. As such, QMC has seen a surge in practical applications and has become the subject of a global development race, with the algorithm demonstrating excellent compatibility with exascale supercomputers.

One notable QMC package is `TurboRVB <https://aip.scitation.org/doi/10.1063/5.0005037>`__., developed by Sandro Sorella at the International School for Advanced Studies (SISSA) in Italy over 20 years, currently led by Dr. Michele Casula (Sorbonne University in France) and Dr. Kosuke Nakano (National Institute for Materials Science (NIMS) in Japan).
