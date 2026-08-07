---
layout: default
title: "ProbNum 2026 &ndash; Programme"
header_image: LUT.jpg
---

## **Tentative programme**

The conference will be held at the Lappeenranta Campus of LUT University ([Yliopistonkatu 34, 53850 Lappeenranta](https://maps.app.goo.gl/T1kWcn4ZjDgJbTr76)). 

---

#### 9 September, 2026 (Wednesday)

09:00&ndash;10:00 Registration & coffee <br> 
10:00&ndash;11:00 **ELLIS Distinguished Lecture** by [Philipp Hennig](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/methoden-des-maschinellen-lernens/personen/philipp-hennig/) (University of Tübingen)<br> 
11:00&ndash;11:20 Break & conference opening <br>
11:20&ndash;12:00 Presentations <br>
12:00&ndash;13:00 Lunch <br>
13:00&ndash;14:00 **Plenary** by [Elizaveta Semenova](https://www.elizaveta-semenova.com/) (Imperial College London) <br>
14:00&ndash;14:40 Presentations <br>
14:40&ndash;15:30 Coffee <br>
15:30&ndash;17:00 Research speed dating <br>
17:00&ndash;19:00 Poster session & ice breaker (posters will remain visible throughout the conference) <br>

---

#### 10 September, 2026 (Thursday)

09:00&ndash;10:30 Tutorial <br>
10:30&ndash;11:00 Coffee <br>
11:00&ndash;12:00 Presentations <br>
12:00&ndash;13:00 Lunch <br>
13:00&ndash;14:00 **Plenary** by [Florian Schäfer](https://f-t-s.github.io/) (New York University): <i> Toward Information Geometric Mechanics </i>
<details>
     <summary><em>Abstract</em></summary>
     <p> Shock waves in high-speed gas dynamics cause severe numerical difficulties for classical solvers and scientific machine learning. They are fundamentally a multiscale problem: While viscous effects ensure smoothness on microscopic scales, shocks manifest as macroscopic discontinuities. This talk begins with the observation that shock formation arises from the flow map reaching the boundary of the manifold of diffeomorphisms. We modify its geometry such that geodesics approach but never reach the boundary. The resulting information geometric regularization (IGR) has smooth solutions while avoiding the excessive dissipation of viscous regularizations, accelerating and simplifying the simulation of flows with shocks. We prove the existence of global strong IGR solutions in the unidimensional pressureless case and illustrate its practical utility on multidimensional examples with complex shock interactions. With S. Bryngelson and other collaborators, we use IGR to conduct the first compressible flow simulation exceeding a quadrillion degrees of freedom. The modified geometry of the diffeomorphism manifold is the information geometry of the mass density. The last part of the talk explains how this observation motivates information geometric mechanics that views the solutions of continuum mechanical PDEs as parameters of probability distributions originating from statistical physics. Replacing the Euclidean geometry of individual particles with the information geometry of statistical families promises performant numerical methods that preserve the positivity of densities and energies and readily integrate with scientific machine learning.
     </p>  
</details>
14:00&ndash;14:40 Presentations <br>
14:40&ndash;15:30 Coffee <br>
15:30&ndash;16:30 Presentations

18:00&ndash;21:00 Conference dinner in the form of a cruise on lake Saimaa aboard [m/s Camilla](https://karelialines.fi/in-english/). The ship will depart from [Lappeenranta Harbour](https://maps.app.goo.gl/qQrcYJ5XQenHpBAW6).

---

#### 11 September, 2026 (Friday)

09:00&ndash;09:30 Tutorial by Tim Weiland (University of Tübingen): <i>Who Polluted the Harbor? A Live ProbNum Investigation </i> 
<details>
     <summary><em>Abstract</em></summary>
     <p> A pollutant is leaking somewhere in a harbor on the Korean coast. Six sensors report noisy
 concentration readings. Where is the leak? In this hands-on session, we answer that
 question live, building the full inference pipeline in Julia from scratch.</p>

 <p>We start small: a GP prior, a 1D Poisson equation, and derivative kernels written out by
 hand. Then we let the machinery take over: information operators turn PDEs, boundary
 conditions, and sensor data into a single language of linear functionals;
 Vecchia approximations replace dense kernel matrices with sparse precision matrices,
 so the approach survives contact with real 2D geometry; and hierarchical modelling promotes
 the unknown source location to a hyperparameter. The finale is fully Bayesian: a
 nested-Laplace scheme computes posterior marginals for the leak location,
 and we watch the posterior tighten as we add sensors to the bay.</p>

 <p>The entire investigation runs in a notebook you can take home and point at your own inverse
 problem.
     </p>  
</details>
09:30&ndash;10:30 Presentations <br>
10:30&ndash;11:00 Coffee <br>
11:00&ndash;12:00 **Plenary** by [Hong Ge](https://mlg.eng.cam.ac.uk/hong/) (University of Cambridge) <br>
12:00&ndash;12:15 **Conclusion of the main conference** <br>
12:15&ndash;13:30 Lunch <br>
13:30&ndash;15:00 Breakout sessions <br>
15:00&ndash;15:30 Coffee <br>
15:30&ndash;17:00 Breakout sessions

--- 

## **Conference Dinner**

The conference dinner will take the form of a cruise on lake Saimaa on the [m/s Camilla](https://karelialines.fi/in-english/) on the evening of 10th September. You must register for the dinner in advance.

---

## **Plenaries**

There will be three plenaries delivered by Elizaveta Semenova, Florian Schäfer and Hong Ge.

#### Plenary 1: [Elizaveta Semenova](https://www.elizaveta-semenova.com/) (13&ndash;14 on 9 September)

Elizaveta Semenova is a Lecturer in Biostatistics, Computational Epidemiology and Machine Learning at Imperial College London, Department of Epidemiology and Biostatistics. She also holds Schmidt Sciences AI2050 Early Career Fellowship. In 2019 she completed a PhD in Epidemiology at the Swiss TPH.

Her work is centered around scalable and flexible methods for spatiotemporal statistics and Bayesian machine learning with applications in epidemiology. Most recently, her focus has been on using deep generative modelling to power MCMC inference in classical spatial statistics.

---

#### Plenary 2: [Florian Schäfer](https://f-t-s.github.io/) (13&ndash;14 on 10 September)

Florian Schäfer is an Assistant Professor at the Courant Institute of Mathematical Sciences at New York University. He received his PhD in applied and computational mathematics at Caltech, working with Houman Owhadi. Before that, he received his Bachelor’s and Master’s degrees in Mathematics at the University of Bonn.

His research interests lie at the interface of numerical computation, statistical inference, and competitive games. His current research focus is on developing information geometric mechanics that uses the statistical physical underpinnings of continuum mechanics to design structure preserving numerical methods at the macroscale.

---

#### Plenary 3: [Hong Ge](https://mlg.eng.cam.ac.uk/hong/) (11&ndash;12 on 11 September)


Hong Ge is a Research Professor at the University of Cambridge, where he is a member of the Machine Learning Group, part of the Computational and Biological Learning Lab in the Department of Engineering.

Together with his colleagues and he explores how intelligence works - mathematically and computationally. His current interests include Bayesian mathematics and neural networks. He also created the Turing probabilistic programming language.

---

Before the start of the conference Philipp Hennig from the University of Tübingen will deliver an [ELLIS Distinguished Lecture](https://www.ellisinstitute.fi/ellis-distinguished-lectures). These lectures showcase cutting-edge artificial intelligence research from top scientists in the field. The lecture will be streamed.

#### ELLIS Distinguished Lecture: [Philipp Hennig](http://mml.cs.uni-tuebingen.de/) (10&ndash;11 on 9 September)

Philipp Hennig is the Professor for the Methods of Machine Learning at the University of Tübingen, and Director of the Tübingen AI Center. Since his PhD with Sir David MacKay in Cambridge, he is interested in the connections between inference and computation, which led him to establish, with international collaborators, the field of probabilistic numerics. Hennig is a Fellow of ELLIS, where he co-directs the Research Program for Theory, Algorithms and Computations for modern learning machines. His work was supported, among others, by Emmy Noether and Max Planck Fellowships, and two ERC grants.

---