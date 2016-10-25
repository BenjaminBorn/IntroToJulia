
# A Deep Introduction to Julia for Data Science and Scientific Computing

## Introduction

This workshop is put together by Chris Rackauckas as part of the UC Irvine Data Science Initiative. This workshop is made to teach people who are experienced with other scripting languages the relatively new language Julia. Unlike the other Data Science Initiative workshops, this workshop assumes prior knowledge of some form of programming in a language such as Python, R, or MATLAB.

We will start by introducing the basic syntax of the language, and quickly move into the details of how Julia is different from other scripting languages and how to exploit Julia's type system + multiple dispatch to be able to achieve C/Fortran-like performance while maintaining the concise syntax of a scripting language. Large parts of the package ecosystem will be explored and some information on implementation details will be highlighted in order for the participants to learn how to design Julia projects.

The ideal participant is anyone who is interested in Julia. There are many groups of people interested in using Julia. One large fraction come with a strong software development background and C/Fortran knowledge, and are looking to learn Julia as a tool to create packages with enhanced productivity while not losing performance. On the other side, there are users who are interested in the growing package ecosystem of Julia and would like to add Julia to their knowledge-base. And then there's everything in between. One major goal of this workshop is to use Julia's language and syntax to bridge the gap between "package users" and "package developers" in the way that Julia has done. 


## Introduction to the Author

Chris is a PhD student in Mathematics from the Mathematical, Computational, and Systems Biology (MCSB) Gateway program and is an active part of the Julia community. He runs the blog, http://www.stochasticlifestyle.com/, where he write tutorials on using the Julia languages covering many topics, such as high-performance and GPGPU computing, package development, and Julia tips. He is part of the JuliaMath and JuliaDiffEq communities for curating the Julia libraries for mathematics and differential equations respectively. Chris is the developer of many Julia packages, the most prominent being [DifferentialEquations.jl](https://github.com/JuliaDiffEq/DifferentialEquations.jl), a Julia library which has become a standard solver for many forms of differential equations.

### Remote Instructors

You are highly encouraged to use the [Julia Gitter chat channel](https://gitter.im/JuliaLang/julia) to ask your Julia-related questions, both during the workshop and after the workshop! There are a few "remote instructors" who will be available through this chat channel at different times throughout the workshop:

- Lyndon White (@oxinabox): University of Western Australia
- Fengyang Wang (@TotalVerb): University of Waterloo
- Ismael Venegas Castelló (@Ismael-VC): Data Analyst at Rich IT

Others will also be available. Please do not be afraid to use this resource!

## Notes Before We Get Started

- Please install some version of IJulia/Jupyter to follow along. I also recommend working through longer problems using the Juno IDE.
- The start of the course will be on developing general performant Julia code. After lunch it will be about the package ecosystem. This understanding of Julia will be useful even for "Julia users" (i.e. non package developers) to use packages effectively, but don't worry we will get to packages. 
- Please do the problems/projects at your own pace. Not everyone is expected to complete all of the material in the allotted time. Instead, this is supposed to be a resource to introduce you to a large amount of Julia, and the material may take awhile to fully be digested. That's okay!
- During the basic introduction, there will be information that is not included in these notebooks. That is intentional. One major hurdle for learning a language is learning how to find out more about the language. Please use the manual, chatrooms, StackExchange, etc. If these aren't working for you, ask for help.

A good primer for the workshop: https://www.youtube.com/watch?v=JNvMs0j3a4E

## Installation and Setup

To get started, see the [Tooling, Documentation, and Community notebook](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/ToolingDocumentationCommunity).

## Rendered Jupyter Notebooks

### Introduction

- [Tooling, Documentation, and Community](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/ToolingDocumentationCommunity)
- [A Mental Model for Julia](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/JuliaMentalModel)
- [A Very Quick Introduction to Git/Github for Julia Users](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/GithubIntroduction)


### Basics

- [A Basic Introduction to Julia](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/BasicIntroduction)
- [Why Julia?](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/WhyJulia)
- [7 Julia Gotchas and How to Handle Them](http://www.stochasticlifestyle.com/7-julia-gotchas-handle/)

### Detailed Usage: A Peak Into "the Rabbit Hole"

- [Metaprogramming](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/Metaprogramming)
- [Call Overloading](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/CallOverloading)
- [More Details on Arrays and Matrices - How to get Fortran Speeds in Linear Algebra](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/ArraysAndMatrices)
- [Array and Iterator Interfaces](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/ArrayIteratorInterfaces)

### Packages to Explore

- [Overview of the Package Ecosystem](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/PackageEcosystem)
- [Data Visualization: Plots.jl]
- Juno, the Julia IDE (Debugging, Progress Bars, etc.): JunoLab
- Differential Equations: DifferentialEquations.jl
- Dimensional Reduction: MultivariateStats.jl
- Mathematical Programming / Optimization: JuMP and Optim.jl
- Solving Nonlinear Equations: NLsolve.jl
- Forward-mode Autodifferentiation: ForwardDiff.jl
- Robust Benchmarking: BenchmarkTools.jl
- Bioinformatics: Bio.jl
- Deep Learning: Mocha.jl, TensorFlow.jl, or MXNet.jl
- Symbolic Mathematics: Symata.jl, SymEngine.jl, and SymPy.jl


### Extra Projects

- [Using External Languages from Julia (Interop)](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/Interop)
- [Parallelism and HPC](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/HPCJulia)
- [Work in Progress: JuliaML for Machine Learning] - Include Roadmap and Tom's post
- Package Development, Documentation, and Testing
- Tools for Faster Code: InplaceOps.jl, CatViews.jl, and VML.jl

### Experiments

Probe around and understand the following results:

- [Type-Stability Experiment](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/TypeStabilityExperiment)
- [Scoping Experiment](http://ucidatascienceinitiative.github.io/IntroToJulia/Html/ScopingExperiment)


---------------------------
# Extras
---------------------------


## Slides

### Introduction

- [Tooling, Documentation, and Community](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/ToolingDocumentationCommunity)
- [A Mental Model for Julia](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/JuliaMentalModel)
- [A Very Quick Introduction to Git/Github for Julia Users](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/GithubIntroduction)

### Basics

- [An Introduction to Basic Julia](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/BasicIntroduction)
- [Why Julia?](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/WhyJulia)

### Detailed Usage: A Peak Into "the Rabbit Hole"

- [Metaprogramming](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/Metaprogramming)
- [Call Overloading](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/CallOverloading)
- [Array and Iterator Interfaces](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/ArrayIteratorInterfaces)
- [More Details on Arrays and Matrices - How to get Fortran Speeds from Linear Algebra](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/ArraysAndMatrices)



### Packages to Explore

- [Overview of the Package Ecosystem](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/PackageEcosystem)
- [An In-Depth Look at Plots.jl](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/PlotsJL)

### Projects / Experiments
- [Type-Stability Experiment](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/TypeStabilityExperiment)
- [Scoping Experiment](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/ScopingExperiment)
- [Parallelism and HPC](http://ucidatascienceinitiative.github.io/IntroToJulia/Slides/HPCProject)

## How These Were Made

This entire repository is made using Jupyter notebooks using the template from the [JupyterSite](https://github.com/ChrisRackauckas/JupyterSite) repository.
