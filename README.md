# Numerical Integration via Gaussian Quadrature

Final project for Numerical Analysis, Colorado College, 2026.

## Overview
This paper examines Gaussian quadrature, a numerical integration method 
that approximates definite integrals using a weighted sum of function 
evaluations at strategically chosen points (nodes). Drawing on several 
sources, it covers the mathematical background and derivation of the 
method, then applies it to specific integration problems.

The accompanying implementation, written in R, applies Gaussian quadrature 
to several test functions and compares the results against known exact 
integrals as the number of nodes increases. It also benchmarks Gaussian 
quadrature's accuracy against Simpson's rule, comparing error as a function 
of the number of function evaluations each method requires.

## Contents
- `gaussian-quadrature.pdf` — full paper: background, derivation, and 
  application of Gaussian quadrature

## Skills Demonstrated
- Derivation and conceptual understanding of a core numerical methods technique
- Literature synthesis — researching and citing multiple technical sources
- Formal technical writing for a mathematical audience
- Numerical implementation and algorithm comparison in R
- Quantitative error analysis and benchmarking against an alternative method

## Tools
R, LaTeX
