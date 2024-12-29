## About me

I am a researcher who recently joined the group of Prof. Dr.-Ing. Henning Wessels at the Institute of Applied Mechanics [(IAM)](https://www.tu-braunschweig.de/iam), which is part of the Technische Universität Braunschweig.

I earned my Bachelor's degree in Control Engineering from Universidad Nacional de Colombia in 2013. Subsequently, I received both my Master's and Ph.D. degrees in Engineering and Chemical Engineering, respectively, from Universidad de Antioquia — the former in 2017 and the latter in 2020.

I have a strong background in applied mathematics and computational methods in engineering. My current research interests focus on addressing the question: How can physics-based models benefit from machine learning techniques to minimize discrepancies between models and real systems, by accurately quantifying the sources of their uncertainties?"

## Ongoing research

**Self-learning methodology for an emplacement section of a deep geological repository (SEMOTI)**

In this project, the potential of machine learning (ML) in modeling repository systems/deep storage systems is investigated. The objective is to adapt advanced ML algorithms for geomechanical applications. In particular, we are interested in the design optimization and monitoring of deep geological repositories for radioactive waste disposal. A key component of the approach is the utilization of Gaussian processes as surrogate models for these repositories.

The proposed research aims to investigate the applicability of ML methods for the underlying parametric mechanical models and to highlight the strengths and weaknesses of automation. The end goal is to achieve a more seamless integration between modeling and real-world data, thereby creating a comprehensive Digital Twin of a deep geological storage system.

**FEM implementation of a coupled diffusion-deformation theory for hydrogels**

Hydrogels are water-swollen, self-supporting polymeric networks. Capable of undergoing extremely large deformations, they also facilitate the diffusion and release of molecules. Given their unique properties, hydrogels have been applied in a broad spectrum of technical applications, particularly within the food and biomedical sectors. Modeling such materials presents a distinct challenge due to the simultaneous deformation of the polymer network and the diffusion of the solvent through this network. Over recent years, a consensus has been emerging in favor of a comprehensive coupled diffusion-deformation theory to depict the behavior of gels. This includes swelling, shrinking, and drying, fluid squeezing due to mechanical deformation, and forced permeation. In conjunction with this, a number of methods concerning the numerical implementation of these theories, designed to solve coupled diffusion-deformation boundary value problems in gels, have been introduced.

Notably, detailed numerical procedures and source codes are rarely provided in scientific journal articles. As a result, realizing the numerical implementation of most coupled theories via the finite element method (FEM) remains a considerable challenge. With this in mind, the primary objective of this project is to delve into the intricacies of the numerical implementation of a foundational coupled diffusion-deformation theory for hydrogels, utilizing the Fenics FEM package.

**Hybrid physics-based and data-driven dynamical systems identification using kernel-based methods**

Real-world systems and phenomena often exhibit nonlinearity. While their behavior can sometimes be approximated with simpler linear models for ease of understanding and interpretation, these approximations typically hold true only within a specific input range. To capture a more comprehensive range of operating conditions, a nonlinear model would be ideal. Yet, formulating precise nonlinear models that accurately reflect real system dynamics is challenging. Furthermore, our understanding of linear systems is typically more profound than that of nonlinear counterparts.

This project delves into the exploration of various strategies for assembling hybrid models that merge physics-based and data-driven dynamics. Our aim is to evaluate their performance capabilities in engineering tasks, such as reliability analysis or closed-loop control. The idea is to combine an optimal linear representation of the system under study-- e.g., optimal in the least square sense-- and extend it to adopt so-called kernel models that can "learn" the system's unmodeled (nonlinear) dynamics. The resulting model is a nonlinear one composed of linear and nonlinear parts. The linear part can be constructed based on some known physics of the real system, which makes it interpretable. The nonlinear part can be identified based on, e.g., measured data computing the error between the linear approximation and the real system. Some well-known kernel models, widely used in Machine Learning applications, could serve as suitable choices for its formulation, e.g., exponential, square exponential, Matern with parameter 3/2 or 5/2 kernels.

## Research roadmap

Since 2016, I have been working on the development of multiscale models of nonlinear dynamical systems. This endeavor led me to study PDE/ODEs – kMC type multiscale models, which can accurately describe a broad range of complex dynamical systems, such as human tissue-like materials and lithium-ion batteries.

For nearly two years, I served as a guest researcher at the Institute of Continuous Mechanics (IKM) at Leibniz Universität Hannover, Germany. One of my primary achievements was the formulation of a numerical solution for PDE/ODEs-kMC multiscale models. This solution was built upon the foundational principles of the finite element method and incorporated various approaches prevalent in fluid and solid mechanics. For example, it utilized algorithms to address elastoplastic models and advection-diffusion problems. Additionally, I employed model order reduction techniques, specifically those based on the proper orthogonal decomposition method, and explored their applications in uncertainty propagation analyses.

The last project I participated in at IKM concerned the regulation of blood glucose levels in type 1 diabetes patients. We evaluated the stability of closed-loop strategies that utilize insulin pumps to regulate blood glucose. We proposed a surrogate model based on Gaussian processes to estimate the stabilizing sets of PID controllers when addressing uncertain nonlinear systems. The outcome of this analysis was a stochastic set, which provides probabilistic insights into the ability of a PID controller to stabilize a non-linear system.

From April 2021 to July 2023, I conducted research at the Institute of Mechanics and Computational Mechanics (IBNM), Leibniz Universität Hannover, Germany, under the guidance of Prof. Udo Nackenhorst. My work at IBNM revolved around uncertainty quantification and the application of numerical methods to problems in continuum mechanics. Random fields representation by Karhunen-Loève expansion, uncertainty propagation through polynomial Chaos expansion, hybrid physics-based and data-driven dynamical systems identification using kernel-based methods applied to high-dimensional (non)linear structural problems, and modeling of functional materials with applications in biomechanics were the main topics of my research at the institute.

Since August 2023, I joined the Data-Driven Modeling of Mechanical Systems group led by Prof. Dr.-Ing. Henning Wessels at the Institute of Applied Mechanics [(IAM)](https://www.tu-braunschweig.de/iam), which is a part of Technische Universität Braunschweig. My primary goal is the uncertainty quantification and surrogate modeling of complex nonlinear multiphysics problems. We aim to explore the capabilities of machine learning methods in the development of digital twins for optimization, calibration, and monitoring of complex engineering problems, such as deep geological repositories for radioactive waste disposal.

## My research interests

*Why and how does complexity emerge in real-world systems?* Much of the world exists outside the scales directly perceivable by humans. Some of these dimensions exist at higher orders of magnitude (considered as the supra-scale), while others are at smaller orders of magnitude (the micro-scale). As a result, the Universe we inhabit is perceived as multiscale. The boundaries between these scales are not always distinct. There's often a nuanced overlap between adjacent scales, leading to intricate interactions among them. In essence, different scales become apparent when one phenomenon becomes obscured as we focus on another. For instance, when you look through a microscope, stars are not visible, and conversely, through a telescope, microbes remain hidden.

I am investigating the complexity of nonlinear dynamical systems. My goal is to gain a deeper understanding of how randomness or unpredictability naturally arises due to our inability to perceive all different scales or dimensions of real-world systems. Single-scale models often fall short, unable to encapsulate all the pertinent details of real nonlinear systems. This limitation can lead to discrepancies between model predictions and actual outcomes, highlighting the gaps in our understanding. On the other hand, multiscale approximations harness a broader spectrum of information about the system, providing deeper insights into the roots of its complexity. Nevertheless, given that many scales in nature remain beyond our observation, it is crucial to comprehend how this missing information affects the phenomena we can observe. To address this, I am delving into frameworks that seamlessly blend multiple scales into cohesive, manageable mathematical models. In pursuit of this, I combine probability theory, stochastic simulation algorithms, and deterministic methods such as ordinary or partial differential equations into a unified multiscale framework, aiming to represent the various scales from the micro to the macroscopic.

## Recent publications

Agarwal, G., Urrea-Quintero, J. H., Wessels, H., & Wick, T. (2024). Parameter identification and uncertainty propagation of hydrogel coupled diffusion-deformation using POD-based reduced-order modeling. Computational Mechanics, 1-31.

Urrea-Quintero, J. H., Marino, M., Wick, T., & Nackenhorst, U. (2024). A comparative analysis of transient finite-strain coupled diffusion-deformation theories for hydrogels. Archives of Computational Methods in Engineering, 1-34.

Basmaji, A. A., Fau, A., Urrea-Quintero, J. H., Dannert, M. M., Voelsen, E., & Nackenhorst, U. (2022). Anisotropic multi-element polynomial chaos expansion for high-dimensional non-linear structural problems. Probabilistic Engineering Mechanics, 70, 103366.

Urrea-Quintero, J. H., Fuhg, J. N., Marino, M., & Fau, A. (2021). PI/PID controller stabilizing sets of uncertain nonlinear systems: an efficient surrogate model-based approach. _Nonlinear Dynamics_, 105(1), 277-299.

Urrea-Quintero, J. H., Marino, M., Hernández, H., & Ochoa, S. (2020). Multiscale modeling of a free-radical emulsion polymerization process: Numerical approximation by the Finite Element Method. _Computers & Chemical Engineering_, 106974.

Urrea-Quintero, J. H., Hernández, H., & Ochoa, S. (2020). Towards a controllability analysis of multiscale systems: application of the set-theoretic approach to a semi-batch emulsion polymerization process. _Computers & Chemical Engineering_, 106833.

You can find a list of my publications on [Google Scholar](https://scholar.google.com/citations?hl=en&user=vxlllIsAAAAJ&view_op=list_works&sortby=pubdate).

## Scholarships, awards, honors

**2020** | Award for an Outstanding Performance and Collaboration of a Visiting Researcher - Faculty of Mechanical Engineering - Leibniz Universität Hannover - Germany.

**2016** | COLCIENCIAS - Scholarship 727/2015 - Colombian Government.

**2014** | “Estudiante Instructor” Scholarship for Master Degree - Universidad de Antioquia - Colombia.

**2013** | Undergraduate Students Award Involved in High Impact Research Activities - Antioquia Department Government -Colombia.
