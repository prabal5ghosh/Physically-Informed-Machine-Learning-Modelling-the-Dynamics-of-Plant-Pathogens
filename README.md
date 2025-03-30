# Physically-Informed-Machine-Learning-Modelling-the-Dynamics-of-Plant-Pathogens
Physically-Informed Machine Learning for Modelling the Dynamics of Plant-Pathogens Molecular Interactions


## Overview
This project explores the modeling of gene expression dynamics using Physics-Informed Neural Networks (PINNs) and Neural Ordinary Differential Equations (Neural ODEs(Parametric) ) and hybrid model( Inverse PINN +Neural ODE(Parametric)). The primary objective is to leverage deep learning models to predict gene expression levels over time, incorporating prior biological knowledge through differential equations.

## Features
- Implementation of PINNs to incorporate biological laws into the model training process.
- Neural ODEs for learning gene expression dynamics without explicit differential equations.
- Neural ODEs (Parametric) for learning gene expression dynamics with explicit differential equations.
- Hybrid model( Inverse PINN + Neural ODE(Parametric) to use the power of both the models.
- Comparison of these methods in predicting gene expression.
- Visualization and analysis of model performance.

## Methodology
1. **Dataset Preparation**
   - Transcriptomics dataset preprocessed for modeling.
2. **Modeling Approaches**
   - **Physics-Informed Neural Networks (PINNs)** 
   - **Neural ODEs(Parametric)**
   - **Hybrid model( Inverse PINN +Neural ODE(Parametric))**

## Results
- PINNs effectively integrate known biological laws, leading to more interpretable models.
- Neural ODEs provide flexibility in learning gene expression patterns without predefined equations.
- Hybrid model( Inverse PINN +Neural ODE(Parametric) performs average.
- Performance comparison for the models are analyzed with experimental data.


## References
- [Physics-Informed Neural Networks (PINNs)](https://arxiv.org/abs/1711.10561)
- [Neural Ordinary Differential Equations](https://arxiv.org/abs/1806.07366)


## License
This project is licensed under the MIT License. See `LICENSE` for details.

