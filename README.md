# The fat-shattering dimension of norm-bounded two-layer ReLU networks in fixed dimension

Yitzchak Shmalo

Consider the functions x ↦ uᵀσ(Wx) on the ball of radius b_x in ℝᵈ, where σ is the ReLU function, W has n rows,
‖W‖_F ≤ B and |u| ≤ b, and put R = bBb_x/ε. For every width and dimension the fat-shattering dimension of this class
at scale ε is at most R² up to logarithmic factors, and Vardi, Shamir and Srebro asked whether a better bound holds
when d is small. For fixed d ≥ 2 the exponent of R is 2(d−1)/(d+2): the fat-shattering dimension is at most a
constant times R^(2(d−1)/(d+2)) log(2+R) for every width, and at least a constant times R^(2(d−1)/(d+2)) when the
width is at least that large. The upper bound writes the networks through support functions of zonoids, as Bach did,
and uses the approximation of zonoids by zonotopes due to Matoušek and Siegel. The lower bound restricts the networks
to an affine hyperplane and uses the embedding of Sobolev spaces into the ReLU variation space due to Mao, Siegel and
Xu.

- `paper/main.tex`, `paper/notation.tex`, `paper/main.pdf`: the paper.

Credits for the results the paper rests on are in `CREDITS.md`.
