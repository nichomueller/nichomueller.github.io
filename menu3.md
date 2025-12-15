@def title = "Software"

# Software

## GridapROMs.jl (Role: Author)

@@im-50
![](/assets/gridaproms.png)
@@

I am the main author of GridapROMs.jl, a free and open-source reduced order modeling package written entirely in Julia. Its goal is to enable the efficient solution of parameterized partial differential equations using a range of state-of-the-art techniques from the reduced order modeling literature. The library includes multiple strategies for compressing full-order finite element manifolds to construct reduced approximation spaces, such as proper orthogonal decomposition, Tucker decomposition, tensor-train decomposition, discrete interpolation methods, and local subspace techniques. It supports a broad spectrum of applications, including linear and nonlinear problems, single- and multi-field systems, coupled equations, as well as steady and transient ones. Distributed-in-memory parallelism is also available for the efficient computation of (expensive) offline operations, such as the generation of snapshots. The package offers a user-friendly, high-level API that is highly interpretable and is easily extensible by users.

> More info:
> - Visit the official [Github repository](https://github.com/gridap/GridapROMs.jl).
> - To get started, take a look at the [documentation](https://gridap.github.io/GridapROMs.jl/dev/).


## MeteoModels.jl (Role: Author)

I am the main author of MeteoModels.jl, a Julia package that provides a collection of tools for data assimilation and uncertainty quantification in real-world dynamical systems, with a particular emphasis on geophysical and weather-related applications. The package currently supports several widely used filtering techniques, including the Kalman Filter (KF) for linear systems, its nonlinear extensions such as the Extended Kalman Filter (EKF) and the Unscented Kalman Filter (UKF), as well as ensemble-based methods like the Ensemble Kalman Filter (EnKF) and its deterministic variant (DEnKF), which reduces sampling noise and mitigates ensemble collapse. Future development is aimed at extending the package with a reduced-basis Ensemble Kalman Filter (RB-EnKF), designed to lower computational costs through projection-based model reduction and enable efficient application to large-scale problems.

@@im-50
![](/assets/meteomodels.png)
@@

> More info:
> - Visit the official [Github repository](https://github.com/nichomueller/MeteoModels.jl).
> - To get started, take a look at the [documentation](https://nichomueller.github.io/MeteoModels.jl/dev/).