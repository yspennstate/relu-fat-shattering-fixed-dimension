# Credits

The question is that of G. Vardi, O. Shamir and N. Srebro, The sample complexity of one-hidden-layer neural
networks (NeurIPS 2022, arXiv:2202.06233), Section 3.2.

The dimension-free bound of order R² for the ReLU class comes from the Rademacher bounds of B. Neyshabur, R. Tomioka
and N. Srebro (COLT 2015, arXiv:1503.00036) and N. Golowich, A. Rakhlin and O. Shamir (Inf. Inference 2020,
arXiv:1712.06541); Vardi, Shamir and Srebro (Theorem 2) extend it to Lipschitz activations. Their Theorem 3 and
Corollary 1 give lower bounds linear in R when d is large.

Upper bound. The connection between ReLU networks and zonoids is due to F. Bach (JMLR 2017, arXiv:1412.8690). The
approximation of zonoids in ℝᵈ by zonotopes with m summands at the rate m^(−1/2−3/(2(d−1))) is due to J. Matoušek
(Acta Math. 1996) for d ≥ 5 and to J. W. Siegel (arXiv:2307.15285, Theorem 1) for d = 3, 4; it is optimal by
J. Bourgain, J. Lindenstrauss and V. Milman (Acta Math. 1989). The planar case is classical (D. E. McClure and
R. A. Vitale, J. Math. Anal. Appl. 1975); the paper proves it with explicit constants. Proposition 1.4 uses Siegel's
uniform approximation theorem for networks with biases (Theorem 2 of the same paper). F. Liu, L. Dadi and V. Cevher
(JMLR 2024, Proposition 5) obtained the exponent 2d/(d+2) for networks with biases when d > 5.

Lower bound. The embedding of the Sobolev space of order (e+3)/2 into the variation space of ReLU networks with
biases is due to T. Mao, J. W. Siegel and J. Xu (arXiv:2408.10996, Theorem 1). The variation norm is that of Bach and
of J. W. Siegel and J. Xu (Found. Comput. Math. 2024).

New in the paper: the lower bound of Theorem 1.2(b), and with it the exponent 2(d−1)/(d+2) of the class.
