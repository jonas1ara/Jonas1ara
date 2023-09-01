<h1 align="center">I'm Jonas Lara</h1>
<h3 align="center">A passionate student of Mathematics and Psicology</h3>

![greece](/1500x500.jpeg)

_I am the reincarnation of some thinker from ancient Greece living the glorious modernity_

## Fourier series, a poem ...

The Fourier series is a branch of Fourier analysis that aims to decompose a periodic function into a sum of exponentials (or trigonometric functions) with different frequencies and magnitudes, in this particular demonstration, we are defining $f(t)$ to be a periodic complex function with $t\in[0, 1]$

Represent $f(t)$ as a sum of exponential functions rotating at frequencies of $0, 1, -1, 2, -2, ...$ rotations per $t$:

$$
f(t) = \dots + c_{-2}e^{-2\cdot 2\pi it} + c_{-1}e^{-1\cdot 2\pi it} + c_{0}e^{0\cdot 2\pi it} + c_{1}e^{1\cdot 2\pi it} + c_{2}e^{2\cdot 2\pi it} + \dots
$$

Taking the integral of the function across its domain:

$$
\int_0^1 f(t) dt
$$

Expanding $f(t)$ in terms of its Fourier series:

$$
\int_0^1 f(t) dt = \int_0^1 (\dots + c_{-1}e^{-1\cdot 2\pi it} + c_{0}e^{0\cdot 2\pi it} + c_{1}e^{1\cdot 2\pi it} + \dots)dt
$$


Distributing the definite integral:

$$
\int_0^1 f(t) dt = \dots + \int_0^1c_{-1}e^{-1\cdot 2\pi it}dt + \int_0^1c_{0}e^{0\cdot 2\pi it}dt + \int_0^1c_{1}e^{1\cdot 2\pi it}dt + \dots
$$
