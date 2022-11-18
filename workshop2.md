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
- 13.15-14.15 Silvia Bertoluzza: [_Coupling black box solvers under minimal assumptions_](#silvia-bertoluzza-coupling-black-box-solvers-under-minimal-assumptions)
- 14.15-15.15 Olaf Steinbach: [_Space-time finite and boundary element methods in electromagnetic simulations_](#olaf-steinbach-space-time-finite-and-boundary-element-methods-in-electromagnetic-simulations)
- 15.15-15.30 Break
- 15.30-16.30 Christophe Geuzaine: [_Weak FEM-BEM coupling for the time-harmonic Maxwell equations_](#chrisophe-geuzaine-weak-fem-bem-coupling-for-the-time-harmonic-maxwell-equations)


### Day 2: 23 November

- 13.00-13.15 Introduction
- 13.15-14.15 Frederic Nataf: [_Adaptive Coarse Space for Saddle Point problem_](#frederic-nataf-adaptive-coarse-space-for-saddle-point-problem)
- 14.15-15.15 Miguel Fernandez: [_Time splitting schemes for incompressible fluid-structure interaction_](#miguel-fernandez-time-splitting-schemes-for-incompressible-fluid-structure-interaction)
- 15.15-15.30 Break
- 15.30-16.30 Mats Larson: [_Applications of Hybridization to Domain Decomposition and Model Coupling_](#mats-larson-applications-of-hybridization-to-domain-decomposition-and-model-coupling)

All times in GMT


#### Registration

[Registration](https://www.eventbrite.co.uk/e/online-workshop-mathematical-theory-of-coupling-methods-for-pdes-tickets-420629453017) is required to access the Zoom Webinar


#### Christophe Geuzaine: _Weak FEM-BEM coupling for the time-harmonic Maxwell equations_
In this talk I will present a well-conditioned weak coupling of
boundary element and high-order finite element methods for
time-harmonic electromagnetic scattering by inhomogeneous objects
[1]. The approach is based on the use of a non-overlapping domain
decomposition method involving quasi-optimal transmission
operators. The associated transmission boundary conditions are
constructed through a localization process based on complex rational
Padé approximants of the nonlocal Magnetic-to-Electric operators. The
number of iterations required to solve this weak coupling is only
slightly dependent on the frequency and the mesh refinement.

[1] Badia, I., Caudron, B., Antoine, X., & Geuzaine, C. (2022). A
well-conditioned weak coupling of boundary element and high-order
finite element methods for time-harmonic electromagnetic scattering by
inhomogeneous objects. SIAM Journal on Scientific Computing, 44(3),
B640-B667.

####  Frederic Nataf: _Adaptive Coarse Space for Saddle Point problem_
We introduce a scalable adaptive element-based domain decomposition
(DD) method for solving saddle point problems defined as a block two
by two matrix. The algorithm does not require any knowledge of the
constrained space. We assume that all sub matrices are sparse and that
the diagonal blocks are spectrally equivalent to a sum of positive
semi definite matrices. The latter assumption enables the design of
adaptive coarse space for DD methods that extends the GenEO theory to
saddle point problems. Numerical results on three dimensional
elasticity problems for steel-rubber structures discretized by a
finite element with continuous pressure are shown for up to one
billion degrees of freedom along with comparisons to Algebraic
Multigrid Methods.

#### Mats Larson: _Applications of Hybridization to Domain Decomposition and Model Coupling_
We present the basic concepts in CutFEM, including stabilization
methods and recent developments on so called extension operators which
essentially eliminates unstable degrees of freedom in such a way that
optimal approximation properties are retained. Then we turn to
hybridization and derive a domain decomposition method and discuss
various ways of choosing the meshes. Finally, we extend the
hybridization approach to model coupling in computational mechanics.

#### Miguel Fernandez: _Time splitting schemes for incompressible fluid-structure interaction_
Mathematical problems describing the mechanical interaction of a
flexible structure with an incompressible fluid flow appear in a wide
variety of engineering fields. Fluid-structure interaction is also
particularly ubiquitous in nature. One can think, for instance, of the
wings of a bird interacting with the air, the fins of a fish moving
through the water, or blood propelled into the arteries. The solid is
deformed under the action of the fluid and the fluid flow is disturbed
by the moving solid. Such multi-physic phenomena are generally
described by heterogeneous systems of non-linear equations with an
interface coupling which can be extremely stiff when solved via
partitioned solution procedures (the so-called added-mass
effect). Over the last fifteen years, the development and analysis of
efficient partitioned methods for these systems has been a very active
field of research. In this talk, we will give an overview of some of
these techniques, with particular emphasis on time splitting schemes.

#### Silvia Bertoluzza: _Coupling black box solvers under minimal assumptions_
We discuss, in a general (abstract) framework, and with concrete
examples, the numerical solution of a global problem formulated,
already at the continuous level, as a system of weakly coupled local
problems.
With an approach similar to the one underlying the FETI domain
decomposition method and treating the local numerical solvers as
black-boxes, we discuss sufficient conditions ensuring stability and
accuracy of the discrete coupled problem, for which we also discuss a
preconditioning strategy (also inspired by FETI).

#### Olaf Steinbach: _Space-time finite and boundary element methods in electromagnetic simulations_
For the eddy current approximation of the Maxwell system to
model an electric motor results in an elliptic-parabolic
interface problem, we introduce and analyze a space-time
variational formulation, and its space-time finite element
discretization. In addition we also discuss the coupling with
boundary elements to model the Laplace equation in the air
domain. For this we recall some results on the non-symmetric
coupling of finite and boundary element methods.