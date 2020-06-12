# FactorVAE
***Not completed to tune parameters.***

A tensorflow 2.0 implementation of the FactorVAE algorithm.

Disentangling by Factorising (Kim & Mnih, 2018) https://arxiv.org/pdf/1802.05983.pdf

You will need to download the file 3dshapes.h5 from https://github.com/deepmind/3d-shapes.

To train the model, run FactorVAE.ipynb

# Validation example
![]{img/Training.png}

# Latent traversal
The hypothesis of the failing latent traversal is overfitting or loss balance and inappropriate hyperparameter because the traversal is partially success.
![]{img/LatentTraversal.png}