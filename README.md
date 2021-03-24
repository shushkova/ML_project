# ML_project
Image Inpainting via Cellular Automata

Final Project of course "Machine Learning" Skoltech 2021

Datasets: MNIST, CelebA can be found there: http://yann.lecun.com/exdb/mnist/, http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html#:~:text=All%20images%20of%20the%20CelebA,Chinese%20University%20of%20Hong%20Kong.

This repository project consist 2 ipynb files: CAInpainting.ipynb, CAInpainting_experiments_metrics__P100_ipynb_.ipynb
and weights for baseline NN with L1 loss : 5epochsL1loss.pt

CAInpainting.ipynb - main ipython notebook of project. MNIST, CelebA.
Implementations of differnet type of mask which used in project
Definition of vanila model and results for MNIST, CelebA
Visualization part with animations(also included)
Definition of GANs model


CAInpainting_experiments_metrics__P100_ipynb_.ipynb - ipython notebook with baseline NN with some experiments and results like
comparison of using L1 vs MSE loss for training NN, and comparison on some quantative metrics: PSNR, SSIM on 5 epochs on CelebA dataset.
