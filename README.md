# REALIST-project

![alt text](https://github.com/nicolaslepagecnam/REALIST-project/blob/main/frame_272_delay-0.1s(1).png)

REALIST (REsiduAl LearnIng of SimulaTion) is an application of hybrid simulation and deep learning techniques to the field of fluid dynamics.
Computational Fluid Dynamics (CFD) is indispensable in a multitude of fields, including aerodynamic optimisation in the automotive and aviation industries, weather forecasting, and medicine. We will investigate a surrogate problem in the field of fluid dynamics, the viscous Burgers' equation: one-dimensional model that mimics the Navier-Stokes equations governing fluid dynamics. Our hybrid simulation method combines an approximate Partial Differential Equation (PDE) model with an end-to-end and time-continuous deep learning method for the correction of the model's residual error.
In addition, this study evaluates a more physically significant loss function based on the Sobolev $H^1$ norm as opposed to the more conventional $ L^2 $ norm. Both the hybrid methodology and the new $H^1$ loss function improve test set performance when compared to a non-hybrid data-driven method or the simplified approximate PDE model.
