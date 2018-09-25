This colab implements the [Symplectic Gradient Adjustment](http://proceedings.mlr.press/v80/balduzzi18a/balduzzi18a.pdf) (SGA) algorithm.
It then applies this optimizer to two different experiments:
* using a GAN to learn a 4 by 4 mixture of Gaussians;
* using a GAN to learn 75 dimensional Gaussian.

All experiments run in 5-10 minutes with a GPU, but can of course be much slower on CPU.

Use this link to run this notebook in colab:
https://colab.research.google.com/github/deepmind/symplectic-gradient-adjustment/blob/master/Symplectic_Gradient_Adjustment.ipynb

