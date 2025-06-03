---
layout: default
title: "ProbNum25 : Schedule"
header_image: juan3.jpg
---


# Tentative Schedule (subject to change) 

**The following is a tentative schedule, created for logistical purposes, and is subject to change significantly.**

---

## 1st September, 2025 (Monday)  
#### Bus: Antibes (9:00, place de gaulle) -> EURECOM

### 10:00 - 11:00: **Tutorial/keynote** 1: TBD

### 11:00 - 11:30: Coffee break + poster session

### 11:30 - 12:00: Demo 1
- **GaussED: A Python Package for Sequential Experimental Design**.
  - Matthew A Fisher, Onur Teymur, Chris J. Oates 
    <details>
    <summary><em>Abstract</em></summary>
    <p> Sequential algorithms are popular for experimental design, enabling emulation, optimisation and inference to be efficiently performed. For most of these applications bespoke software has been developed, but the approach is general and many of the actual computations performed in such software are identical. Motivated by the diverse problems that can in principle be solved with common code, this paper presents GaussED, a high-level syntax coupled to a powerful experimental design engine in Python, which together automate sequential experimental design for approximating a (possibly nonlinear) quantity of interest in Gaussian processes models. Using a handful of commands, GaussED can be used to: solve linear partial differential equations, perform tomographic reconstruction from integral data, implement Bayesian optimisation with gradient data, and emulate a complex computer model. </p>  </details>

### 12:00 - 12:30: Demo 2
- **A Dictionary of Closed-Form Kernel Mean Embeddings**.
  - Francois-Xavier Briol, Toni Karvonen, Alexandra Gessner, Maren Mahsereci
    <details>
    <summary><em>Abstract</em></summary>
    <p> Kernel mean embeddings -- integrals of a kernel with respect to a probability distribution -- are essential in Bayesian quadrature, but also widely used in other computational tools for numerical integration or methods for statistical inference. These methods often require, or are enhanced by, the availability of a closed-form expression for the kernel mean embedding. However, deriving such expressions can be challenging, limiting the applicability of kernel-based techniques when practitioners do not have access to a closed-form embedding. This paper addresses this limitation by providing a comprehensive dictionary of known kernel mean embeddings, along with practical tools for deriving new embeddings from known ones. We also provide a Python library that includes minimal implementations of the embeddings. </p>  </details>
    
### 12:30 - 14:00: Lunch break

### 14:00 - 15:00: **Tutorial/keynote** 2: TBD

### 15:00 - 16:00: Coffee break + poster

### 16:00 - 16:30: Demo 3
- **Adaptive Probabilistic ODE Solvers Without Adaptive Memory Requirements**.
   - Nicholas Krämer
     <details>
     <summary><em>Abstract</em></summary>
     <p>
     Despite substantial progress in recent years, probabilistic solvers with adaptive step sizes can still not solve memory-demanding differential equations
     unless we care only about a single point in time (which is far too restrictive; we want the whole time series). Counterintuitively, the culprit is the adaptivity itself: Its unpredictable memory demands easily exceed our machine's capabilities, making our simulations fail unexpectedly and without warning. Still, dropping adaptivity would abandon years of progress, which can't be the answer. In this work, we solve this conundrum. We develop an adaptive probabilistic solver with fixed memory demands building on recent developments in robust state estimation. Switching to our method (i) eliminates memory issues for long time series, (ii) accelerates simulations by orders of magnitude through unlocking just-in-time compilation, and (iii) makes adaptive probabilistic solvers compatible with scientific computing in JAX.
     </p>  </details>

### 16:30 - 17:00: Talk 1
- **Fixing the Pitfalls of Probabilistic Time-Series Forecasting Evaluation by Kernel Quadrature**.
  - Masaki Adachi, Masahiro Fujisawa, Michael A Osborne. 
    <details>
    <summary><em>Abstract</em></summary>
    <p>Despite the significance of probabilistic time-series forecasting models, their evaluation metrics often involve intractable integrations. The most widely used metric, the continuous ranked probability score (CRPS), is a strictly proper scoring function; however, its computation requires approximation. We found that popular CRPS estimators—specifically, the quantile-based estimator implemented in the widely used GluonTS library and the probability-weighted moment approximation—both exhibit inherent estimation biases. These biases lead to crude approximations, potentially resulting in improper rankings of forecasting model performance. To address this, we introduced a kernel quadrature approach that leverages an unbiased CRPS estimator and employs cubature construction for scalable computation. Empirically, our approach consistently outperforms the two widely used CRPS estimators.</p>  </details>  

#### Bus: EURECOM (17:30) -> Antibes (place de gaulle)

---

## 2nd September, 2025 (Tuesday)  
Bus: Antibes (9:00, place de gaulle) -> EURECOM

10:00 - 11:00: **Tutorial/keynote** 3: TBD

11:00 - 11:30: Coffee break + poster

11:30 - 12:00: Talk 2: **Solving Einstein's equations as Bayesian regression**  

12:00 - 12:30: Talk 3: **Fast Gaussian process regression for high dimensional functions with derivative information**

12:30 - 14:00: Lunch break  

14:00 - 14:30: Talk 4: **Natural Evolutionary Search meets Probabilistic Numerics**
 
14:30 - 15:00: Talk 5: **Online Conformal Probabilistic Numerics via Adaptive Edge-Cloud Offloading** 


15:00 - 16:00: Coffee break + poster

16:00 - 16:30: Talk 6: **Effects of Interpolation Error and Bias on the Random Mesh Finite Element Method for Inverse Problems**  

Bus: Eurecom (17:00)  -> Nice  (Excursion + Conference dinner)

Bus: Nice (10:30) -> Antibes (place de gaulle)

---

## 3rd September, 2025 (Wednesday)  

Bus: Antibes (9:00, place de gaulle) -> EURECOM

10:00 - 10:30: Talk 7: **Learning to Solve Related Linear Systems**
 
10:30 - 11:00: Talk 8: **Bayesian autoregression to optimize temporal Matérn-kernel Gaussian process hyperparameters**

11:00 - 11:30: Coffee break + poster

11:30 - 12:00: Talk 9: **Propagating Model Uncertainty through Filtering-based Probabilistic Numerical ODE Solvers**

12:00 - 12:30: Talk 10: **Randomised Postiterations for Calibrated BayesCG**

12:30 - 14:00: Lunch break 

14:00 - 14:30: Closing

--- 

