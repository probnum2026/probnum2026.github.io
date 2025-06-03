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

### 15:00 - 16:00: Coffee break + poster session

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
#### Bus: Antibes (9:00, place de gaulle) -> EURECOM

### 10:00 - 11:00: **Tutorial/keynote** 3: TBD

### 11:00 - 11:30: Coffee break + poster session

### 11:30 - 12:00: Talk 2:  
- **Solving Einstein's equations as Bayesian regression**.
  - Frederik De Ceuster, Tom Colemont, Tjonnie G.F. Li
    <details>
    <summary><em>Abstract</em></summary>
    <p> Gravitational waves (GWs) are revolutionising our fundamental understanding of physics and cosmology. However, the numerical modelling required to turn their measurement into a scientific detection poses a formidable computational challenge. In this paper, we explore whether a Bayesian view can help enhance the computational efficiency of GW source models. As a proof-of-principle, we pose the solution of the Einstein equations, which relate the dynamics of spacetime to its matter content, as a Bayesian regression problem. By choosing natural priors, based on Green's functions of the relevant operators, we open up ways to better target computing power in our numerical models. Therefore, we conclude that probabilistic numerics is a promising approach to overcome the computational challenges in GW science. </p> </details>

### 12:00 - 12:30: Talk 3:
- **Fast Gaussian process regression for high dimensional functions with derivative information**.
  - Aleksei Sorokin, Pieterjan Robbe, Fred J Hickernell
    <details>
    <summary><em>Abstract</em></summary>
    <p>  Gaussian process regression (GPR) is the backbone of many methods in probabilistic numerics. Exact GPR on \(n\) sampling locations in \(d\) dimensions generally costs \(\mathcal{O}(n^3)\) to fit and requires \(\mathcal{O}(n^2)\) storage. Using certain pairings of sampling locations and kernels induces nice structure into the Gram matrix and enables accelerated exact GPR. One popular pairing uses Cartesian grids with product kernels to induce Kronecker structure in the Gram matrix. This reduces exact GP fitting costs to \(\mathcal{O}(d n^{3/d})\) and storage requirements to \(\mathcal{O}(d n^{2/d})\), but quickly becomes intractable when the dimension exceeds a few dozen. Recent work has shown that pairings of certain low-discrepancy sequences with special kernels enable GPR to scale like \(\mathcal{O}(n \log n)\) for fitting costs and \(\mathcal{O}(n)\) for storage requirements.  We describe an extension of these methods to problems which observe \(m\) derivative multi-indices at each of the \(n\) low-discrepancy sampling locations.  By exploiting similar structure across blocks of the Gram matrix, we are able to reduce the GP fitting cost from \(\mathcal{O}(n^3 m^3)\) to \(\mathcal{O}(n^2 \log n + m^3 n)\) and reduce the storage requirements from \(\mathcal{O}(n^2 m^2)\) to \(\mathcal{O}(n m^2)\).  We explore a number of synthetic benchmarks to illustrate the potential of the proposed approach.
    </p> </details>
    
### 12:30 - 14:00: Lunch break  

### 14:00 - 14:30: Talk 4:  
- **Natural Evolutionary Search meets Probabilistic Numerics**.
  - Pierre Osselin, Masaki Adachi, Xiaowen Dong, Michael A Osborne
    <details>
    <summary><em>Abstract</em></summary>
    <p> Zeroth-order local optimisation algorithms are essential for solving real-valued black-box optimisation problems. Among these, Natural Evolution Strategies (NES) represent a prominent class, particularly well-suited for scenarios where prior distributions are available. By optimising the objective function in the space of search distributions, NES algorithms naturally integrate prior knowledge during initialisation, making them effective in settings such as semi-supervised learning and user-prior belief frameworks. However, due to their reliance on random sampling and Monte Carlo estimates, NES algorithms can suffer from limited sample efficiency. In this paper, we introduce a novel class of algorithms, termed Probabilistic Natural Evolutionary Strategy Algorithms (ProbNES), which enhance the NES framework with Bayesian quadrature. We show that ProbNES algorithms consistently outperforms their non-probabilistic counterparts as well as global sample efficient methods such as Bayesian Optimisation (BO) or $\pi$BO across a wide range of tasks, including benchmark test functions, data-driven optimisation tasks, user-informed hyperparameter tuning tasks and locomotion tasks. </p> </details>
 
### 14:30 - 15:00: Talk 5: 
- **Online Conformal Probabilistic Numerics via Adaptive Edge-Cloud Offloading**.
  - Qiushuo Hou, Sangwoo Park, Matteo Zecchin, Yunlong Cai, Guanding Yu, Osvaldo Simeone
    <details>
    <summary><em>Abstract</em></summary>
    <p> Consider an edge computing setting in which a user submits queries for the solution of a linear system to an edge processor, which is subject to time-varying computing availability. The edge processor applies a probabilistic linear solver (PLS) so as to be able to respond to the user’s query within the allotted time and computing budget. Feedback to the user is in the form of an uncertainty set. Due to model misspecification, the uncertainty set obtained via a direct application of PLS does not come with coverage guarantees with respect to the true solution of the linear system. This work introduces a new method to calibrate the uncertainty sets produced by PLS with the aim of guaranteeing long-term coverage requirements. The proposed method, referred to as online conformal prediction-PLS (OCP-PLS), assumes sporadic feedback from cloud to edge. This enables the online calibration of uncertainty thresholds via online conformal prediction (OCP), an online optimization method previously studied in the context of prediction models. The validity of OCP-PLS is verified via experiments that bring insights into trade-offs between coverage, prediction set size, and cloud usage. </p </details>

### 15:00 - 16:00: Coffee break + poster session

### 16:00 - 16:30: Talk 6:  
- **Effects of Interpolation Error and Bias on the Random Mesh Finite Element Method for Inverse Problems**.
  - Anne Poot, Iuri Rocha, Pierre Kerfriden, Frans van der Meer
    <details>
    <summary><em>Abstract</em></summary>
    <p> Bayesian inverse problems are an important application for probabilistic solvers of partial differential equations: when fully resolving numerical error is computationally infeasible, probabilistic solvers can be used to consistently model the error and propagate it to the posterior. In this work, the performance of the random mesh finite element method (RM-FEM) is investigated in a Bayesian inverse setting. We show how interpolation error negatively affects the RM-FEM posterior, and how these negative effects can be diminished. In scenarios where FEM is biased for a quantity of interest, we find that RM-FEM struggles to accurately model this bias. </p> </details>


#### Bus: Eurecom (17:00)  -> Nice  (Excursion + Conference dinner)

#### Bus: Nice (10:30) -> Antibes (place de gaulle)

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

