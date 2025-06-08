## Overview

This repository presents novel approaches based on the **ergodicity metric** introduced in the paper:

> **"Metrics for Ergodicity and Design of Ergodic Dynamics for Multi-Agent Systems"**  
> George Mathew and Igor Mezić  
> [Read the paper](https://www.sciencedirect.com/science/article/abs/pii/S016727891000285X?fr=RR-2&ref=pdf_download&rr=9442fb44dae4e522)

These methods extend ergodic control techniques for trajectory optimization and spatial coverage, with potential applications in robotics, exploration, and autonomous systems.

---

### Acknowledgements

Some portions of the code are adapted from:

- [MurpheyLab/ergodic-control-sandbox](https://github.com/MurpheyLab/ergodic-control-sandbox)

---

### Notebooks Overview

#### 🌀 Ergodic Metric Optimization (FFT-based)
- `SMC_ergodic_control_FFT.ipynb`  
  ![](imgs/Fourier_properties.png)  
  ![](imgs/Radius=0.01.png)

#### 📡 Alternative Sensor Measures
- `smc_ergodic_sensor_distributions.ipynb`  
  ![](imgs/Uniform_0.01.png)  
  ![](imgs/Uniform_0.1.png)

#### 🚗 Ergodicity Under Unicycle Model
- `smc_ergodic_unicycle.ipynb`  
  ![](imgs/Radius=0.01.png)

#### 🔢 Different Basis Function Sets
- `smc_ergodic_different_basis.ipynb`
