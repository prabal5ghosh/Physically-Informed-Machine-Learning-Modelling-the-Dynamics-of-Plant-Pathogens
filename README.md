# Physically-Informed-Machine-Learning-Modelling-the-Dynamics-of-Plant-Pathogens
Physically-Informed Machine Learning for Modelling the Dynamics of Plant-Pathogens Molecular Interactions

                  	Name - Prabal Ghosh
			Course- Research Project
                        Msc Data Science and Artificial Intelligence (M2)
                        Université Côte d’Azur, Sophia Antipolis, France
			 


## Acknowledgments

Supervisor: **Prof. Silvia Bottini**

Institution: INRAe/UniCA


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

1. Sören Becker, Michal Klein, Alexander Neitz, Giambattista Parascandolo, and Niki Kilbertus. *Discovering ordinary differential equations that govern time-series.* arXiv preprint arXiv:2211.02830, 2022.  
2. Yunpeng Cao, Xiaoxu Li, Hui Song, Muhammad Abdullah, and Muhammad Aamir Manzoor. *Multi-omics and computational biology in horticultural plants: from genotype to phenotype, volume II.* 2024.  
3. Ricky TQ Chen, Yulia Rubanova, Jesse Bettencourt, and David K Duvenaud. *Neural ordinary differential equations.* Advances in Neural Information Processing Systems, 31, 2018.  
4. Salvatore Cuomo, Vincenzo Schiano Di Cola, Fabio Giampaolo, Gianluigi Rozza, Maziar Raissi, and Francesco Piccialli. *Scientific machine learning through physics-informed neural networks: Where we are and what’s next.* Journal of Scientific Computing, 92(3):88, 2022.  
5. Rossin Erbe, Genevieve Stein-O’Brien, and Elana J Fertig. *Transcriptomic forecasting with neural ordinary differential equations.* Patterns, 4(8), 2023.  
6. Laurent Girin, Simon Leglaive, Xiaoyu Bie, Julien Diard, Thomas Hueber, and Xavier Alameda-Pineda. *Dynamical variational autoencoders: A comprehensive review.* arXiv preprint arXiv:2008.12595, 2020.  
7. Alex Glyn-Davies, Connor Duffin, O Deniz Akyildiz, and Mark Girolami. *φ-DVAE: Physics-informed dynamical variational autoencoders for unstructured data assimilation.* Journal of Computational Physics, 515:113293, 2024.  
8. Paguiel Javan Hossie, Béatrice Laroche, Thibault Malou, Lucas Perrin, Thomas Saigre, and Lorenzo Sala. *Simulating interactions in microbial communities through physics-informed neural networks: Towards interaction estimation.* 2024.  
9. George Em Karniadakis, Ioannis G Kevrekidis, Lu Lu, Paris Perdikaris, Sifan Wang, and Liu Yang. *Physics-informed machine learning.* Nature Reviews Physics, 3(6):422–440, 2021.  
10. Diederik P Kingma, Max Welling, et al. *An introduction to variational autoencoders.* Foundations and Trends® in Machine Learning, 12(4):307–392, 2019.  
11. Isaac E Lagaris, Aristidis Likas, and Dimitrios I Fotiadis. *Artificial neural networks for solving ordinary and partial differential equations.* IEEE Transactions on Neural Networks, 9(5):987–1000, 1998.  
12. Lu Lu, Xuhui Meng, Zhiping Mao, and George Em Karniadakis. *DeepXDE: A deep learning library for solving differential equations.* SIAM Review, 63(1):208–228, 2021.  
13. Chuizheng Meng, Sungyong Seo, Defu Cao, Sam Griesemer, and Yan Liu. *When physics meets machine learning: A survey of physics-informed machine learning.* arXiv preprint arXiv:2203.16797, 2022.  
14. Maziar Raissi, Paris Perdikaris, and George E Karniadakis. *Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations.* Journal of Computational Physics, 378:686–707, 2019.  
15. Yulia Rubanova, Ricky TQ Chen, and David K Duvenaud. *Latent ordinary differential equations for irregularly-sampled time series.* Advances in Neural Information Processing Systems, 32, 2019.  
16. Jeyachandran Sivakamavalli and Baskaralingam Vaseeharan. *An overview of omics approaches: Concept, methods, and perspectives.* 2020.  
17. Xiaoyu Zhang, Jingqing Zhang, Kai Sun, Xian Yang, Chengliang Dai, and Yike Guo. *Integrated multi-omics analysis using variational autoencoders: Application to pan-cancer classification.* In 2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM), pages 765–769. IEEE, 2019.  
18. Kookjin Lee and Eric J Parish. *Parameterized neural ordinary differential equations: Applications to computational physics problems.* Proceedings of the Royal Society A, 477(2253):20210162, 2021.

## Contributors

Prabal Ghosh(@prabal5ghosh)

<a href="https://univ-cotedazur.eu/msc/msc-data-science-and-artificial-intelligence" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/fr/thumb/f/fa/Logo-univ-nice-cote-dazur.svg/587px-Logo-univ-nice-cote-dazur.svg.png?20211016184305" alt="Université Côte d'Azur" />
</a>


## License
This project is licensed under the MIT License. See `LICENSE` for details.

