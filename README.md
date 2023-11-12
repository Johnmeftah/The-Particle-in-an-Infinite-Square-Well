# Abstract
In this recitation, we explore the quantum mechanical system of a particle confined in a one-dimensional
infinite square-well potential. Utilizing the time-independent Schr ̈odinger wave equation, we examine the
wave functions that describe the system’s quantum states and the resulting physical observables. The
infinite square-well potential, ideal for studying quantum confinement, illustrates the quantization of
energy levels and the spatial distribution of a particle within such a potential

# Infinite Square-Well Potential in Quantum Mechanics

The infinite square-well potential is a fundamental model in quantum mechanics, illustrating energy quantization and wave function behavior. This model's potential, \( V(x) \), is defined as zero within the well (\( 0 < x < L \)) and infinite outside it, confining the particle strictly within \( x = 0 \) and \( x = L \).

## Schrödinger Wave Equation

For this system, the Schrödinger wave equation is defined as:

\[
V(x) = 
\begin{cases} 
\infty & \text{for } x \leq 0, x \geq L, \\
0 & \text{for } 0 < x < L.
\end{cases}
\]

Within the well, the particle is free, and the wave function \( \psi(x) \) satisfies the time-independent Schrödinger equation with \( V = 0 \):

\[
\frac{d^2\psi}{dx^2} = -k^2\psi,
\]

where \( k \) is related to the energy \( E \) by \( k = \sqrt{2mE/\hbar^2} \). The general solution to this equation is a superposition of sine and cosine functions:

\[
\psi(x) = A \sin(kx) + B \cos(kx),
\]

To satisfy the boundary conditions (\( \psi(0) = \psi(L) = 0 \)), we find \( B = 0 \) and \( kL = n\pi \), where \( n \) is a positive integer. This leads to the quantized wave functions:

\[
\psi_n(x) = A \sin\left(\frac{n\pi x}{L}\right), \quad n = 1, 2, 3, \ldots
\]

## Analysis

These equations serve as the basis for our analysis of the probability density and energy levels of the particle in the infinite square-well potential.

> **Reference:**  
> Stephen T. Thornton and Andrew Rex. *Modern Physics for Scientists and Engineers*. 4th ed. 2012, p. 212.


