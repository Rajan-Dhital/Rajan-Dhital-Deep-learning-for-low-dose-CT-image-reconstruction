# Rajan-Dhital-Deep-learning-for-low-dose-CT-image-reconstruction
A CT scan or Computed Tomography scan is the process of getting a cross-sectional interior image
of the body without direct observation. The images generated from the CT scan are called Sinograms
which are produced by the line integrals of the projections of X-rays under different angles. Tomo-
graphic reconstruction is the inverse problem where the interior structure of the body is reconstructed
from these Sinograms.
The high dose of X-rays used in the CT scan causes harmful effects on the patients. To prevent the
effects of high-dose X-ray radiation, a low dose of X-ray can be the solution. However, when a low
dose of X-ray is used, the quality of the image is degraded drastically. The key idea of this paper is to
check the possibility of construction of better quality images even with the low dose of X-rays.
Mathematically, sinogram (f~) can be formulated by multiplication of input image (~u) with the radon
matrix (A).
f = A ∗ u
(1)
The construction of the image from equation (1) is the inverse problem. However, the simple inverse
of the radon matrix will not work because the low dose of X-ray makes the problem ill-posed. Instead
of simple inverse, Pseudo-inverse can be the way to get the approximate solution of the ill-posed
problem.
A clean and clear image is not possible to construct by the use of pseudo-inverse because the first,
pseudo-inverse gives only the approximate solution, and the second, noise is also generated during the
generation of sinogram by the CT scan. To remove the noises of constructed image, a learning-based
approach (Deep learning) is used, which optimizes the parameters of the network and removes noises
from the constructed image.
