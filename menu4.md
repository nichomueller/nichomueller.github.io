@def title = "Research"
<!--@def hascode = true-->
@def mintoclevel=2 
@def maxtoclevel=4

# Research

<!--\toc-->
\tableofcontents

\label{career}
## Framing my research career 

In this introductory section I pinpoint the field of application of my research, and some general features of the problems within this field that my research targets. This will help the reader understand my trajectory and the main {{rls}} I have carried out, which are covered in Section [Past research, trajectory, and main research lines](#sec_rt_rl).

As a researcher working in the {{cse}} field, I contribute to the development of computational models, algorithms, and software for several application problems. All of these share three common general features (not restricted to, though):

1. The physical phenomena to be simulated are governed by a (potentially highly nonlinear) {{pde}}, or more generally, by a system of {{pdes}}. These phenomena may span multiple temporal and spatial scales, and involve different physical models.
1. The system of {{pdes}} is discretized by means of the {{fem}}. Thus, broadly speaking, the simulation pipeline encompasses three main ingredients: mesh generation and partitioning, space-time {{fe}} discretization, and solution of (non)linear system(s) of equations.
1. These are application problems with ever increasing modelling accuracy requirements, and thus highly demanding from the computational viewpoint. In particular, simulation pipelines grounded on highly parallel, algorithmically scalable algorithms and {{hpc}} software, thus able to efficiently exploit the vast amount of computational resources in current petascale supercomputers, are required in order to achieve the aforementioned modelling requirements.

The increasing levels of complexity both in terms of algorithms and hardware make the development of scientific software able to tackle the aforementioned features, while running efficiently on state-of-the-art numerical algorithms on {{hpc}} resources, a scientific challenge in itself. *A part of my research work has been devoted towards the achievement of this goal.* This is motivated by the fact that research on advanced, newly developed {{fe}} discretizations and solution algorithms for the {{hpc}} solution of {{cse}} complex problems frequently requires **innovative solutions on the software engineering aspects of a numerical software package as well**, and that these latter also represent an important contribution to other researchers working in the {{cse}} community. 

<!--
I am indeed co-founder, main software architect and project coordinator of `FEMPAR`(available at [https://github.com/fempar/fempar](https://github.com/fempar/fempar)), an open-source, scientific software package for the numerical modelling of problems governed by {{pde}} on {{hpc}} platforms. I am also contributor to `Gridap.jl` (available at [https://github.com/gridap/Gridap.jl](https://github.com/gridap/Gridap.jl)), and co-author of `gridapdistributed.jl` (available at [https://github.com/gridap/GridapDistributed.jl](https://github.com/gridap/GridapDistributed.jl)), its parallel message-passing version, which provide a new {{fe}} framework written in Julia for such a purpose. These latter two packages exploit the modern features of the Julia programming language (available at [https://julialang.org/](https://julialang.org/)) in order to strike a remarkable balance among performance and generality via appropriate mathematically-driven software abstractions.