## About me

I am a researcher who in 2021 joined the group of Professor Udo Nackenhorst at the Institute of Mechanics and Computational Mechanics [(IBNM)](https://www.ibnm.uni-hannover.de/en/) in the Leibniz Universität Hannover. I received my Bachelor in Control Engineer at Universidad Nacional de Colombia in 2013, my Master’s degree in Engineering from Universidad de Antioquia in 2017, and my Ph.D. degree in Chemical Engineering at Universidad de Antioquia Colombia in 2020.

I have a strong background in applied mathematics and computational methods in engineering. My current research interests are placed on contributing to answering the longstanding question of: how physics-based models can benefit from machine learning techniques to minimize models and real systems mismatches by accurately quantifying their uncertainty sources?

## Research roadmap

Since 2016 I have been working on the development of multiscale models of nonlinear dynamical systems. I developed a three-scale dynamical model that describes the dynamics of the synthesis of core/shell type polymers in batch polymerization reactors and reduced-order approximations. This development led me to study PDE/ODEs – kMC type multiscale models, which are powerful enough to describe a wide range of complex dynamical systems, e.g., human tissue-like materials and lithium-ion batteries.

For almost 2 years I was a guest researcher at the Institute of Continuous Mechanics (IKM), Leibniz Universität Hannover, Germany. As the foremost outcome, I formulated a consistent solution of PDE/ODEs – kMC multiscale models using the finite element method, multiple approaches widely studied in the area of fluid mechanics and solid mechanics (for instance, algorithms to solve elasto-plastic models and advection-diffusion problems), as well as, model order reduction techniques based on the proper orthogonal decomposition method and its application in uncertainty propagation analyses.

The latest development at IKM I was involved in was related to the blood glucose level regulation in type 1 diabetes patients. We analyzed the stability of the closed-loop strategies to regulate blood glucose based on insulin pumps. A Gaussian process-based surrogate model was proposed to estimate stabilizing sets of PID controllers tackling uncertain nonlinear systems. The result of the random analysis is a stochastic set providing probability information regarding the capabilities of a PID controller to stabilize the non-linear system.

At IBNM, I have been researching uncertainty quantification and numerical methods applied to continuum mechanics problems. Random fields representation by Karhunen-Loève expansion, uncertainty propagation through polynomial Chaos expansion, hybrid physics-based and data-driven dynamical systems identification using kernel-based methods applied to high-dimensional (non)linear structural problems, and modeling of functional materials with applications in biomechanics are the main topics of my current research at the institute.

## My research interests

*Why and how does complexity emerge in real-world systems?* A huge part of the world exists outside scales reachable from humans' perception. Part of such dimensions exists at higher orders of magnitude (let's say at the supra-scale), whereas another part exists at smaller orders of magnitude (the micro-scale). Therefore, the Universe where we live is perceived as multiscale. The boundaries between the scales in the real world are blurry. There is always a fuzzy overlap between adjacent scales that usually leads to complex interactions among them. In principle, different scales are present whenever you lose sight of some phenomenon after focusing on another one. If you look through a microscope, you cannot see stars. If you look through a telescope, you cannot see microbes.

I am investigating the complexity of nonlinear dynamical systems. I want to understand better how randomness or unpredictability emerges naturally due to our inability to perceive all different scales or dimensions of real-world systems. Single-scale models are unable to capture all the relevant information of real nonlinear systems leading to some mismatching between predictions and reality, reflecting the amount of relevant information is missing. On the other hand, multiscale approximations increase the available information about the system, opening the possibility of a better understanding of the source of the complexity. However, since many different scales in nature remain unobservable to us, it is important to know how that missing information influences observable phenomena. For that, I am exploring frameworks that integrate multiple-scale into consistent tractable mathematical models. To that end, I combine probability theory, stochastic simulation algorithms, and deterministic approaches as ordinary or partial differential equations in a single multiscale framework to model the different scales ranging from the micro to the macroscopic.

## Ongoing research

**FEM implementation of a coupled diffusion-deformation theory for hydrogels**

Hydrogels consist in a water-swollen and self-supporting polymeric network. They can undergo extremely large deformations and permit the diffusion and release of molecules. Hydrogels have found applicability in a wide range of technical applications, especially in the food and biomedical fields. Modeling this type of material is a challenging task. It involves concurrent deformation of the polymer network and diffusion of the solvent through the network. In recent years, there has been a convergence towards a more complete coupled diffusion-deformation theory for describing the response of gels---including swelling, shrinking, and drying, squeezing of fluid by applied mechanical deformation, and forced permeation. Additionally, several methods related to the numerical implementation of these theories for solving coupled diffusion-deformation boundary value problems for gels have been published. 

Because detailed numerical procedures and source codes are seldom published in scientific journal papers, the numerical implementation of most of the coupled theories using the finite element method (FEM) is often a challenging task. Therefore, the main purpose of this project is to discuss the details of the numerical implementation of a simple coupled diffusion-deformation theory for hydrogels using Fenics FEM package.


**Hybrid physics-based and data-driven dynamical systems identification using kernel-based methods**

Many real-life systems and phenomena are nonlinear. Their behavior can often be approximated by linear models that are easy to understand and interpret. Unfortunately, linear approximations are only valid for a given input range. One remedy would be developing a nonlinear model that captures a broader range of operating conditions. However, developing sophisticated nonlinear models that capture the real system dynamics reasonably is a demanding task. Additionally, linear systems are better understood than nonlinear ones.

This project focuses on exploring the different alternatives to assemble so-called hybrid physics-based and data-driven dynamical models and exploring their performance capabilities in engineering tasks such as reliability analysis or closed-loop control. The idea is to combine an optimal linear representation of the system under study-- e.g., optimal in the least square sense-- and extend it to adopt so-called kernel models that can "learn" the system's unmodeled (nonlinear) dynamics. The resulting model is a nonlinear one composed of linear and nonlinear parts. The linear part can be constructed based on some known physics of the real system, which makes it interpretable. The nonlinear part can be identified based on, e.g., measured data computing the error between the linear approximation and the real system. Some well-known kernel models, widely used in Machine Learning applications, could be adopted for its construction, e.g., exponential, square exponential, Matern with parameter 3/2 or 5/2 kernels.

## Recent publications

Urrea-Quintero, J. H., Fuhg, J. N., Marino, M., & Fau, A. (2021). PI/PID controller stabilizing sets of uncertain nonlinear systems: an efficient surrogate model-based approach. _Nonlinear Dynamics_, 105(1), 277-299.

Urrea-Quintero, J. H., Marino, M., Hernández, H., & Ochoa, S. (2020). Multiscale modeling of a free-radical emulsion polymerization process: Numerical approximation by the Finite Element Method. _Computers & Chemical Engineering_, 106974.

Urrea-Quintero, J. H., Hernández, H., & Ochoa, S. (2020). Towards a controllability analysis of multiscale systems: application of the set-theoretic approach to a semi-batch emulsion polymerization process. _Computers & Chemical Engineering_, 106833.

Urrea-Quintero, J. H., Ochoa, S., & Hernández, H. (2019). A reduced-order multiscale model of a free-radical semibatch emulsion polymerization process. _Computers & Chemical Engineering_, 127, 11-24.

You can find a list of my publications on [Google Scholar](https://scholar.google.com/citations?hl=en&user=vxlllIsAAAAJ&view_op=list_works&sortby=pubdate).

## Scholarships, awards, honours

**2020** | Award for an Outstanding Performance and Collaboration of a Visiting Researcher - Faculty of MechanicalEngineering - LUH - Germany.

**2016** | COLCIENCIAS - grant 727/2015 - Colombian Government.

**2014** | “Estudiante Instructor” Scholarship for Master Degree - Universidad de Antioquia - Colombia.

**2013** | Undergraduate Students Award Involved in High Impact Research Activities - Antioquia Department Government -Colombia.
