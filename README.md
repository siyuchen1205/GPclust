colvb
=====

Collapsed Variational Bayes, based on the recent NIPS paper:

Fast Variational Inference in the Conjugate Exponential Family
James Hensman, Magnus Rattray, Neil D. Lawrence

http://arxiv.org/abs/1206.5162

Currently implemented models include

LDA - Latent Dirichlet Allocation
MOG - Maixture of Gausians
MMOG - Multiple MOG (which is kind of like a continuous version of LDA)
MOHGP - Mixtures of Hierarchical Gaussian Processes

Other files are common to several models:
col_vb contains a skeleton for the class, and includes the optimiser
col_mix contains the base class for a mixture model (MOG, MOHGP)

This work depends on some functionality from the GPy project (https://github.com/SheffieldML/GPy). I've tested the demos with GPy v0.2.
