---
layout: default
title: "ProbNum25 : Accepted Papers"
header_image: Juan2.jpg
---
## Posters 

---
- **Non-Linear Bayesian Probabilistic Numerical Methods do not Compute Bayesian Posteriors**.
  - Marvin Pförtner. 
    <details>
    <summary><em>Abstract</em></summary>
    <p>Bayesian probabilistic numerical methods rely heavily on the notion of disintegration of measures to construct the posterior. However, due to the implicit nature of their definition, constructing disintegrations is often difficult. A folklore result in machine learning conflates the construction of a disintegration with the restriction of probability density functions onto the subset of events that are consistent with a given observation. We provide a comprehensive set of mathematical tools which can be used to construct disintegrations and apply these to find densities of disintegrations on differentiable manifolds. Using our results, we provide a disturbingly simple example in which the restricted density and the disintegration density drastically disagree. Motivated by applications in approximate Bayesian inference and Bayesian inverse problems, we further study the modes of disintegrations. We show that the recently introduced notion of a "conditional mode" does not coincide in general with the modes of the conditional measure obtained through disintegration, but rather the modes of the restricted measure. We also discuss the implications of the discrepancy between the two measures in practice, advocating for the utility of both approaches depending on the modelling context.</p>  </details>  
  
---
- **Bayesian Inference of Ordinary Differential Equations Accounting for Discretization Error**.
  - Shoji Toyota, Yuto Miyatake
    <details>
    <summary><em>Abstract</em></summary>
    <p> Bayesian inference for ordinary differential equation (ODE) parameters typically relies on numerical solvers; however, incorporating the discretization errors introduced by these solvers into uncertainty quantification is not straightforward. We propose a method to overcome this difficulty. Our approach explicitly models the discretization error as a random variable and jointly performs Bayesian inference on both the ODE parameters and the variance of the discretization error. We demonstrate the effectiveness of the proposed method using the FitzHugh–Nagumo equation model. </p>  </details>
    
---
- **Smoothness Estimation in Spherical Matérn Gaussian Processes**.
  - Subhendu Pramanick
    <details>
    <summary><em>Abstract</em></summary>
    <p> Matérn Gaussian processes are a cornerstone of spatial statistics and machine learning, offering flexible modeling of spatial phenomena through a tunable smoothness parameter. On the sphere-an essential model for global spatial data, two central challenges are: (1) the consistent estimation of the smoothness parameter, which governs the regularity of the process and impacts prediction accuracy, and (2) the quantification of uncertainty, as captured by posterior contraction rates in Bayesian inference. This poster surveys key theoretical advances up to 2025, including the consistent estimation of the smoothness parameter and the Bayesian learning of functions via posterior contraction rates.  Simultaneously, we demonstrate that the smoothness parameter can be consistently estimated from data observed at quasi-uniform points on the sphere, using the maximizer of the Gaussian likelihood—even when the underlying process is non-Gaussian. </p>  </details>

---
- **Bayesian Optimization with Inhomogeneous Smoothness**.
  - Olivier Dondjio
    <details>
    <summary><em>Abstract</em></summary>
    <p> Bayesian optimization (BO) is a popular global optimization technique that uses a Gaussian Process (GP) as a surrogate model for the objective function. Traditional BO methods often assume a stationary GP kernel, implying uniform smoothness across the input space. However, many real‑world objective functions exhibit heterogeneous smoothness. To address this limitation, we propose a BO framework that employs locally adaptive estimation of GP kernel hyperparameters, allowing the model to better capture smoothness variation between regions. </p>  </details>
    
---
- **Sparse Probabilistic Richardson Extrapolation**.
  - Chris Oates
    <details>
    <summary><em>Abstract</em></summary>
    <p> Almost every numerical task can be cast as extrapolation with respect to the fidelity or tolerance parameter of a consistent numerical method.  This perspective enables probabilistic uncertainty quantification and optimal experimental design functionality to be deployed, and also unlocks the potential for convergence of the numerical method to be accelerated.  Recent work established Probabilistic Richardson Extrapolation as a proof of concept, demonstrating how parallel multi-fidelity simulation can be used to accelerate simulation from a whole heart model.  However, the number of data was required to increase super-exponentially with dimension, limiting use in the multivariate context.  This new work develops the notion of `extrapolation sparsity', which is satisfied by most modern numerical methods and provides a promising route to reducing the data requirement.  Sparsity-exploiting methodology is developed that is simultaneously simpler and more powerful compared to earlier work, and this is accompanied by sharp theoretical guarantees. </p>  </details>

---
- **Graph-informed importance sampling for piecewise deterministic Markov processes**.
  - Chennetier Guillaume
    <details>
    <summary><em>Abstract</em></summary>
    <p> Piecewise Deterministic Markov Processes (PDMPs) describe deterministic dynamical systems with parameters subject to random jumps, making them versatile tools for modeling complex phenomena. However, generating their trajectories can be computationally expensive. For a large class of inference problems, an optimal sampling strategy exists and relies on a generalized version of the “committor function” of the process. We propose a novel adaptive importance sampling method to efficiently generate rare trajectories of PDMPs. The approach involves a two-phase process. In a first offline phase, the PDMP is approximated by a simpler process on a graph, enabling explicit computation of key quantities used to build a low-cost approximation of the committor function. In a second online phase, PDMP trajectories are generated using a distribution informed by this approximation and iteratively refined via cross-entropy minimization. We provide asymptotic guarantees and demonstrate the method’s effectiveness by estimating the failure probability of a complex industrial system. </p>  </details>

---
- **Information-Geometric Optimization for computing quantile-based robustness indices**.
  - Baalu-Belay Ketema
    <details>
    <summary><em>Abstract</em></summary>
    <p> In the framework of uncertainty quantification (UQ) of computer codes (denoted G hereinafter), the role of probabilistic robustness methods is important in cases of presence of uncertainty on the probability distribution of the inputs of G. These two-step UQ methods consist in: (a) perturbing the input probability distributions of the computer code, (b) assessing the worst effect of the input perturbation on a quantity of interest (e.g. a quantile) of the output. In this communication, we focus on the second step which corresponds to an optimization problem on a parametric family of probability distributions. The objective function is a quantile of the output of G which depends on the parametric distribution of the input X. We discuss the specificity of this problem and the approach taken to solving it, which is based on natural evolution strategies and information-geometric optimization methods. An application to a toy case and an industrial case-study conclude the poster presentation. </p>  </details>

---
- **Optimal kernel regression bounds under energy-bounded noise**.
  - Amon Lahr
    <details>
    <summary><em>Abstract</em></summary>
    <p> Non-conservative uncertainty bounds are key for both assessing an estimation algorithm’s accuracy and in view of downstream tasks, such as its deployment in safety-critical contexts. In this paper, we derive a tight, non-asymptotic uncertainty bound for kernel-based estimation, which can also handle correlated noise sequences. Its computation relies on a mild norm-boundedness assumption on the unknown function and the noise, returning the worst-case function realization within the hypothesis class at an arbitrary query input location. The value of this function is shown to be given in terms of the posterior mean and covariance of a Gaussian process for an optimal choice of the measurement noise covariance. By rigorously analyzing the proposed approach and comparing it with other results in the literature, we show its effectiveness in returning tight and easy-to-compute bounds for kernel-based estimates. </p>  </details>

---

