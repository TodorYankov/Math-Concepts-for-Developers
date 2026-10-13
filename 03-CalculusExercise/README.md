# 03 â€” Calculus Exercise

## Math Concepts for Developers

Seven solved practical exercises connecting calculus, numerical methods, mathematical modeling, and Python programming. The Jupyter Notebook includes mathematical explanations, executable code, numerical results, and visualizations.

## Completed Exercises

1. **Derivatives and Slope at a Point** â€” numerical differentiation, tangent-line equations, and graphical interpretation of derivatives.
2. **Limits and Euler's Number** â€” numerical investigation of limits and approximations of the mathematical constant *e*.
3. **Derivatives of Exponential Functions** â€” comparing exponential functions with their derivatives, including the special behavior of \(e^x\).
4. **Integrals and Area** â€” numerical integration using the trapezoidal rule, including approximation of the area of a unit circle.
5. **Taylor Series** â€” approximating sine and cosine functions with polynomial expansions and examining approximation errors.
6. **Calculus in Medical Data: Electrocardiography (EKG)** â€” synthesizing an ECG signal, calculating numerical derivatives, detecting R-peaks, and estimating heart rate.
7. **Physics Engine** â€” two-dimensional vector operations, Newton's second law, semi-implicit Euler integration, gravitational motion, and one-dimensional elastic collision simulation.

## Key Mathematical Concepts

- Limits, derivatives, and tangent lines
- Exponential functions and Euler's number
- Definite integrals and numerical approximation
- Taylor polynomials and approximation error
- Numerical differentiation of time-series signals
- Vector algebra, forces, acceleration, and numerical integration
- Conservation of linear momentum and kinetic energy

## Selected Numerical Results

The notebook includes the following numerical checks and simulation outputs:

| Experiment | Result |
| --- | --- |
| Integral of \(x^2\) from 0 to 1 | Approximately 0.33333334 (exact: 1/3) |
| Unit-circle area | Approximately 3.14158933 (exact: Ï€) |
| Synthetic ECG heart rate | 75 BPM |
| Elastic collision: final velocities | âˆ’3.2 m/s and 2.8 m/s |
| Total momentum before and after collision | Approximately 2 kgÂ·m/s |
| Total kinetic energy before and after collision | 22 J |
| Detected collision time in discrete simulation | Approximately 1.234 s |

The numerical values depend on the parameters and discretization used in the exercises.

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- SciPy

## Notebook

The complete exercise, with code, formulas, explanations, and plots, is available here:

ðŸ““ [Open Calculus Exercise](./CalculusExercise.ipynb)

## Limitations and Scope

This is an educational numerical-computing project. The ECG signal is synthetic and is not intended for medical diagnosis. The physics engine demonstrates two-dimensional motion and a simplified one-dimensional elastic collision; it is not a general-purpose physics simulator. Numerical methods introduce approximation errors.

## References & Learning Resources

The following are useful references for the mathematical methods and Python libraries used in this module:

- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/stable/)
- [NumPy â€” Gradient](https://numpy.org/doc/stable/reference/generated/numpy.gradient.html)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [SciPy â€” Signal Processing](https://docs.scipy.org/doc/scipy/reference/signal.html)
- [Khan Academy â€” Calculus](https://www.khanacademy.org/math/calculus-1)
- [Wolfram MathWorld](https://mathworld.wolfram.com/)

### Notes

The implementations, numerical experiments, visualizations, and conclusions were developed as practical work for the **Math Concepts for Developers** course. The reference links above are provided for further study and verification of mathematical and library concepts.

---

**Status:** âœ“ Completed

