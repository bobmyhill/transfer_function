# InSight lander-regolith elastic interactions

This FEniCS model contains very simple finite element modelling of the interaction between the InSight lander and the regolith.

The aim of the model is to produce forward models of the static transfer function between the lander and SEIS deployment, making different assumptions about the elastic properties of the regolith. 

At the moment, the Poisson ratio is constant (0.25) and the Young's modulus is only depth dependent (linear and power law models are contained in the code).

The eventual goal is to add load-dependent properties, as the force exerted on the regolith by the lander is probably sufficient to significantly increase the Young's modulus.
