---
layout: page
title: Online Workshop - Mathematical Theory of Coupling Methods for Partial Differential Equations
---

## 22-23 November 2022

Topics include (but are not restricted to) multi-physics coupling
problems, interface problems, multi-domain problems, preconditioning
of high frequency scattering, multi-methods coupling (such as
FEM/BEM).

### Day 1: 22 November

- 13.00-13.15 Introduction
- 13.15-14.15 Silvia Bertoluzza
- 14.15-15.15 Olaf Steinbach
- 15.15-15.30 Break
- 15.30-16.30 Christophe Geuzaine: [_Weak FEM-BEM coupling for the time-harmonic Maxwell equations_](#chrisophe-geuzaine-weak-fem-bem-coupling-for-the-time-harmonic-maxwell-equations)


### Day 2: 23 November

- 13.00-13.15 Introduction
- 13.15-14.15 Frederic Nataf: [_Adaptive Coarse Space for Saddle Point problem_](#frederic-nataf-adaptive-coarse-space-for-saddle-point-problem)
- 14.15-15.15 Miguel Fernandez
- 15.15-15.30 Break
- 15.30-16.30 Mats Larson

All times in GMT


#### Registration

[Registration](https://www.eventbrite.co.uk/e/online-workshop-mathematical-theory-of-coupling-methods-for-pdes-tickets-420629453017) is required to access the Zoom Webinar


#### Christophe Geuzaine: _Weak FEM-BEM coupling for the time-harmonic Maxwell equations_
In this talk I will present a well-conditioned weak coupling of boundary element and high-order finite element methods for time-harmonic electromagnetic scattering by inhomogeneous objects [1]. The approach is based on the use of a non-overlapping domain decomposition method involving quasi-optimal transmission operators. The associated transmission boundary conditions are constructed through a localization process based on complex rational Padé approximants of the nonlocal Magnetic-to-Electric operators. The number of iterations required to solve this weak coupling is only slightly dependent on the frequency and the mesh refinement.

[1] Badia, I., Caudron, B., Antoine, X., & Geuzaine, C. (2022). A well-conditioned weak coupling of boundary element and high-order finite element methods for time-harmonic electromagnetic scattering by inhomogeneous objects. SIAM Journal on Scientific Computing, 44(3), B640-B667.

####  Frederic Nataf: _Adaptive Coarse Space for Saddle Point problem_
We introduce a scalable adaptive element-based domain decomposition (DD) method for solving saddle point problems defined as a block two by two matrix. The algorithm does not require any knowledge of the constrained space. We assume that all sub matrices are sparse and that the diagonal blocks are spectrally equivalent to a sum of positive semi definite matrices. The latter assumption enables the design of adaptive coarse space for DD methods that extends the GenEO theory to saddle point problems. Numerical results on three dimensional elasticity problems for steel-rubber structures discretized by a finite element with continuous pressure are shown for up to one billion degrees of freedom along with comparisons to Algebraic Multigrid Methods.
