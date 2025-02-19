## Optimized DS Modulation

1. Folder **matlab_scripts** contains various matlab codes supportiung method development. This folder is not necessary to run any simulation
2. Folder **python_scripts** contains codes required to learn implicit distance representation and run simulation.

   a. Folder **python_scripts/mlp_learn** is needed to learn various toy examples for visualization purposes.
   
   a. Folder **python_scripts/ds_mppi** contains required code to run planar robot simulations, pybullet franka simulations and real robot experiments.




## Full Supplementary Video 
This video showcases method explanation, simulation & real robot application
[![Full Supplementary Video](http://img.youtube.com/vi/PmbGwdXiWOc/0.jpg)](https://www.youtube.com/watch?v=PmbGwdXiWOc)


## Method intuition on planar 2d robot

Standard Modulated Dynamical System
![Standard Modulated Dynamical System](https://github.com/epfl-lasa/OptimalModulationDS/assets/22716499/1350e3e4-c0d4-47fd-9700-186dd911f53a)

Proposed method
![Proposed method](https://github.com/epfl-lasa/OptimalModulationDS/assets/22716499/141867f3-3562-4abf-9efb-2aea109cc260)

To run corresponding simulation please navigate to  
```cd python_scripts/ds_mppi/scripts```  
and run either  
```python3 standalonePlanar2d.py``` for simulation  
or  
```python3 standalonePlanar2d_policyPlots.py``` for same simulation, but with more visualizations (for MPPI and navigation kernels). Note that these plots increase the runtime.

To run 7d planar robot use ```python3 standalonePlanar7d.py``` (not as refined)

## Franka simulation in shelf-like environment
![shelf](https://github.com/epfl-lasa/OptimalModulationDS/assets/22716499/c09470f3-6adf-421c-b704-d316392e73fd)

![shelf_anim](https://github.com/epfl-lasa/OptimalModulationDS/assets/22716499/f82c028c-2361-473c-b6c4-4cb73352b561)
