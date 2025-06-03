---
layout: default
title: "ProbNum25 : Accepted Papers"
header_image: Juan2.jpg
---
## Accepted Papers

 ---
- **Fixing the Pitfalls of Probabilistic Time-Series Forecasting Evaluation by Kernel Quadrature**.
  - Masaki Adachi, Masahiro Fujisawa, Michael A Osborne. 
    <details>
    <summary><em>Abstract</em></summary>
    <p>Despite the significance of probabilistic time-series forecasting models, their evaluation metrics often involve intractable integrations. The most widely used metric, the continuous ranked probability score (CRPS), is a strictly proper scoring function; however, its computation requires approximation. We found that popular CRPS estimators—specifically, the quantile-based estimator implemented in the widely used GluonTS library and the probability-weighted moment approximation—both exhibit inherent estimation biases. These biases lead to crude approximations, potentially resulting in improper rankings of forecasting model performance. To address this, we introduced a kernel quadrature approach that leverages an unbiased CRPS estimator and employs cubature construction for scalable computation. Empirically, our approach consistently outperforms the two widely used CRPS estimators.</p>  </details>  
  
---
- **GaussED: A Python Package for Sequential Experimental Design**.
  - Matthew A Fisher, Onur Teymur, Chris J. Oates 
    <details>
    <summary><em>Abstract</em></summary>
    <p> Sequential algorithms are popular for experimental design, enabling emulation, optimisation and inference to be efficiently performed. For most of these applications bespoke software has been developed, but the approach is general and many of the actual computations performed in such software are identical. Motivated by the diverse problems that can in principle be solved with common code, this paper presents GaussED, a high-level syntax coupled to a powerful experimental design engine in Python, which together automate sequential experimental design for approximating a (possibly nonlinear) quantity of interest in Gaussian processes models. Using a handful of commands, GaussED can be used to: solve linear partial differential equations, perform tomographic reconstruction from integral data, implement Bayesian optimisation with gradient data, and emulate a complex computer model. </p>  </details>
    
 ---
- **Adaptive Probabilistic ODE Solvers Without Adaptive Memory Requirements**.
   - Nicholas Krämer
     <details>
     <summary><em>Abstract</em></summary>
     <p>
     Despite substantial progress in recent years, probabilistic solvers with adaptive step sizes can still not solve memory-demanding differential equations
     unless we care only about a single point in time (which is far too restrictive; we want the whole time series). Counterintuitively, the culprit is the adaptivity itself: Its unpredictable memory demands easily exceed our machine's capabilities, making our simulations fail unexpectedly and without warning. Still, dropping adaptivity would abandon years of progress, which can't be the answer. In this work, we solve this conundrum. We develop an adaptive probabilistic solver with fixed memory demands building on recent developments in robust state estimation. Switching to our method (i) eliminates memory issues for long time series, (ii) accelerates simulations by orders of magnitude through unlocking just-in-time compilation, and (iii) makes adaptive probabilistic solvers compatible with scientific computing in JAX.
     </p>  </details>
  
 ---
- **Propagating Model Uncertainty through Filtering-based Probabilistic Numerical ODE Solvers**.
  - Dingling Yao, Filip Tronarp, Nathanael Bosch
    <details>
    <summary><em>Abstract</em></summary>
    <p>Filtering-based probabilistic numerical solvers for ordinary differential equations (ODEs), also known as ODE filters, have been established as efficient methods for quantifying numerical uncertainty in the solution of ODEs. In practical applications, however, the underlying dynamical system often contains uncertain parameters, requiring the propagation of this model uncertainty to the ODE solution. In this paper, we demonstrate that ODE filters, despite their probabilistic nature, do not automatically solve this uncertainty propagation problem. To address this limitation, we present a novel approach that combines ODE filters with numerical quadrature to properly marginalize over uncertain parameters, while accounting for both parameter uncertainty and numerical solver uncertainty. Experiments across multiple dynamical systems demonstrate that the resulting uncertainty estimates closely match reference solutions. Notably, we show how the numerical uncertainty from the ODE solver can help prevent overconfidence in the propagated uncertainty estimates, especially when using larger step sizes. Our results illustrate that probabilistic numerical methods can effectively quantify both numerical and parametric uncertainty in dynamical systems. </p>  </details>
  
 ---
- **Fast Gaussian process regression for high dimensional functions with derivative information**.
  - Aleksei Sorokin, Pieterjan Robbe, Fred J Hickernell
    <details>
    <summary><em>Abstract</em></summary>
    <p>  Gaussian process regression (GPR) is the backbone of many methods in probabilistic numerics. Exact GPR on \(n\) sampling locations in \(d\) dimensions generally costs \(\mathcal{O}(n^3)\) to fit and requires \(\mathcal{O}(n^2)\) storage. Using certain pairings of sampling locations and kernels induces nice structure into the Gram matrix and enables accelerated exact GPR. One popular pairing uses Cartesian grids with product kernels to induce Kronecker structure in the Gram matrix. This reduces exact GP fitting costs to \(\mathcal{O}(d n^{3/d})\) and storage requirements to \(\mathcal{O}(d n^{2/d})\), but quickly becomes intractable when the dimension exceeds a few dozen. Recent work has shown that pairings of certain low-discrepancy sequences with special kernels enable GPR to scale like \(\mathcal{O}(n \log n)\) for fitting costs and \(\mathcal{O}(n)\) for storage requirements.  We describe an extension of these methods to problems which observe \(m\) derivative multi-indices at each of the \(n\) low-discrepancy sampling locations.  By exploiting similar structure across blocks of the Gram matrix, we are able to reduce the GP fitting cost from \(\mathcal{O}(n^3 m^3)\) to \(\mathcal{O}(n^2 \log n + m^3 n)\) and reduce the storage requirements from \(\mathcal{O}(n^2 m^2)\) to \(\mathcal{O}(n m^2)\).  We explore a number of synthetic benchmarks to illustrate the potential of the proposed approach.
    </p> </details>
  
 ---
- **Natural Evolutionary Search meets Probabilistic Numerics**.
  - Pierre Osselin, Masaki Adachi, Xiaowen Dong, Michael A Osborne
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Randomised Postiterations for Calibrated BayesCG**.
  - Niall Vyas, Disha Hegde, Jon Cockayne
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **A Dictionary of Closed-Form Kernel Mean Embeddings**.
  - Francois-Xavier Briol, Toni Karvonen, Alexandra Gessner, Maren Mahsereci
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Effects of Interpolation Error and Bias on the Random Mesh Finite Element Method for Inverse Problems**.
  - Anne Poot, Iuri Rocha, Pierre Kerfriden, Frans van der Meer
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Learning to Solve Related Linear Systems**.
  - Disha Hegde, Jon Cockayne
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Bayesian autoregression to optimize temporal Matérn-kernel Gaussian process hyperparameters**.
  - Wouter M. Kouw
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Solving Einstein's equations as Bayesian regression**.
  - Frederik De Ceuster, Tom Colemont, Tjonnie G.F. Li
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---
- **Online Conformal Probabilistic Numerics via Adaptive Edge-Cloud Offloading**.
  - Qiushuo Hou, Sangwoo Park, Matteo Zecchin, Yunlong Cai, Guanding Yu, Osvaldo Simeone
    <details>
    <summary><em>Abstract</em></summary>
    <p> </p>
  </details>
  
 ---



 
 
