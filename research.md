---
layout: page
title: Research
subtitle: 
---

### Working Papers
-----

**"Spooky Boundaries at a Distance: Inductive Bias, Dynamic Models, and Behavioral Macro"**  
Accept subject to Major Revisions, **Journal of Monetary Economics**

<details>
<summary>Details</summary>
<p>With: <a href="https://www.sas.upenn.edu/~jesusfv/">Jesús Fernández-Villaverde</a>, <a href="https://sebastian-gomezcardona.com/">Sebastián Gómez-Cardona</a>, <a href="https://www.jesseperla.com/">Jesse Perla</a>, <a href="https://janrosa.org/">Jan Rosa</a></p>
<p><a href="docs/Papers/SpookyBoundary.pdf">Download</a> &nbsp;|&nbsp; Slides (<a href="https://mekahou.github.io/docs/Slides/spooky_short.pdf">short</a>, <a href="https://mekahou.github.io/docs/Slides/spooky_long.pdf">long</a>) &nbsp;|&nbsp; <a href="https://github.com/Mekahou">Code</a> &nbsp;|&nbsp; <a href="https://cepr.org/voxeu/columns/spooky-boundaries-distance-inductive-bias-dynamic-models-and-behavioural-macro">VoxEU-CEPR Column</a></p>
<p>In the long run, we are all dead. Nonetheless, when studying the short-run dynamics of economic models, it is crucial to consider boundary conditions that govern long-run, forward-looking behavior, such as transversality conditions. We demonstrate that machine learning (ML) can automatically satisfy these conditions due to its inherent inductive bias toward finding flat solutions to functional equations. This characteristic enables ML algorithms to solve for transition dynamics, ensuring that long-run boundary conditions are approximately met. ML can even select the correct equilibria in cases of steady-state multiplicity. Additionally, the inductive bias provides a foundation for modeling forward-looking behavioral agents with self-consistent expectations.</p>
</details>

---

**"Solving Models of Economic Dynamics with Ridgeless Kernel Regressions"**  
Revise and Resubmit, **Quantitative Economics**

<details>
<summary>Details</summary>
<p>With: <a href="https://www.jesseperla.com/">Jesse Perla</a> and <a href="https://geoffpleiss.com/">Geoff Pleiss</a></p>
<p><a href="https://arxiv.org/abs/2406.01898">Download</a> &nbsp;|&nbsp; <a href="https://mekahou.github.io/docs/Slides/kernel_short.pdf">Slides</a> &nbsp;|&nbsp; <a href="https://github.com/Mekahou">Code</a></p>
<p>This paper proposes a ridgeless kernel method for solving infinite-horizon, deterministic, continuous-time models in economic dynamics, formulated as systems of differential-algebraic equations with asymptotic boundary conditions (e.g., transversality). Traditional shooting methods enforce the asymptotic boundary conditions by targeting a known steady state---which is numerically unstable, hard to tune, and unable to address cases with steady-state multiplicity. Instead, our approach solves the underdetermined problem without imposing the asymptotic boundary condition, using regularization to select the unique solution fulfilling transversality among admissible trajectories. In particular, ridgeless kernel methods recover this path by selecting the minimum norm solution, coinciding with the non-explosive trajectory. We provide theoretical guarantees showing that kernel solutions satisfy asymptotic boundary conditions without imposing them directly, and we establish a consistency result ensuring convergence within the solution concept of differential-algebraic equations. Finally, we illustrate the method in canonical models and demonstrate its ability to handle problems with multiple steady states.</p>
</details>

---

**"Exploiting Symmetry in High-Dimensional Dynamic Programming"**

<details>
<summary>Details</summary>
<p>With: <a href="https://www.sas.upenn.edu/~jesusfv/">Jesús Fernández-Villaverde</a>, <a href="https://www.jesseperla.com/">Jesse Perla</a>, <a href="https://arnavsood.com/">Arnav Sood</a></p>
<p><a href="docs/Papers/symmetry_dynamic_programming.pdf">Download</a> &nbsp;|&nbsp; <a href="https://mekahou.github.io/docs/Slides/symmetry_dynamic_programming_presentation.pdf">Slides</a> &nbsp;|&nbsp; <a href="https://github.com/Mekahou">Code</a></p>
<p>We propose a new method for solving high-dimensional dynamic programming problems and recursive competitive equilibria with a large (but finite) number of heterogeneous agents using deep learning. We avoid the curse of dimensionality thanks to three complementary techniques: (1) exploiting symmetry in the approximate law of motion and the value function; (2) constructing a concentration of measure to calculate high-dimensional expectations using a single Monte Carlo draw from the distribution of idiosyncratic shocks; and (3) designing and training deep learning architectures that exploit symmetry and concentration of measure. As an application, we find a global solution of a multi-firm version of the classic Lucas and Prescott (1971) model of investment under uncertainty. First, we compare the solution against a linear-quadratic Gaussian version for validation and benchmarking. Next, we solve the nonlinear version where no accurate or closed-form solution exists. Finally, we describe how our approach applies to a large class of models in economics.</p>
</details>

---

**"Optimal Entry Decision with Correlated Variable Cost and Output Price"**

<details>
<summary>Details</summary>
<p><a href="docs/Papers/input_output.pdf">Download</a></p>
<p>In models with irrecoverable investment and uncertainty in the output price it is a well-established result that uncertainty increases the output price that a firm starts investment. This paper studies a model of irrecoverable investment (entry) where the variable cost and output price are characterized by two correlated geometric Brownian motions. The numerical results indicate that in the presence of high levels of correlation the impact of uncertainty in output price is ambiguous and depends on the level of variable cost. Specifically, increasing uncertainty in output prices increases the entry output price for low levels of variable cost and the reverse happens for high levels of variable cost. Therefore, in the presence of high levels of correlation the conventional result does not hold anymore. Moreover, this study establishes that increasing the correlation level decreases the entry output price.</p>
</details>

---

### Work in Progress
-----

**"The Blessings of Overparameterization"**

<details>
<summary>Details</summary>
<p>With: <a href="https://www.sas.upenn.edu/~jesusfv/">Jesús Fernández-Villaverde</a></p>
</details>

---

### Publications
-----

**["Modelling the 'S Curve': Transition Dynamics in EV Adoption"](https://iopscience.iop.org/article/10.1088/2515-7620/ae2cf1/pdf)**  
**Environmental Research Communications** (2025)

<details>
<summary>Details</summary>
<p>With: Omid Khajehdehi, <a href="https://alanhastings.ucdavis.edu/">Alan Hastings</a>, <a href="https://www.hastingssimon.com/">Sara Hastings-Simon</a></p>
</details>

---

**["Macroprudential Policy: A Review"](https://www.sciencedirect.com/science/article/abs/pii/S1572308916302297)**  
**Journal of Financial Stability** (2017)

<details>
<summary>Details</summary>
<p>With: <a href="https://haskayne.ucalgary.ca/haskayne_info/profiles/alfred-lehar">Alfred Lehar</a></p>
</details>

---

**["Quantum Search with Interacting Bose-Einstein Condensates"](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.88.032310)**  
**Physical Review A** (2013)

<details>
<summary>Details</summary>
<p>With: <a href="https://profiles.ucalgary.ca/david-lionel-feder">David L. Feder</a></p>
</details>
