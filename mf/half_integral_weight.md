title: Half-integral weight modular forms
authors:
    nsirolli

Let $k$ be an odd integer, and let $N$ a positive integer divisible by $4$. Let $\chi$ be a <a knowl="lmfdb/character.dirichlet">character</a> modulo $N$. A **modular form of half-integral <a knowl="lmfdb/mf.elliptic.weight">weight</a>** $k/2$ , <a knowl="lmfdb/mf.elliptic.level">level</a> $N$ and character $\chi$ is an holomorphic function defined on the upper half plane $\mathcal{H}$, satisfying the transformation formula
\[
f(\gamma z) = \chi(d) j(\gamma, z)^k f(z)
\]
for every $\gamma=\left(\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}\right)\in\Gamma_0(N)$ and $z\in \mathcal{H}$, and being holomorphic at the <a knowl="lmfdb/mf.sl2z.subgroup.cusps">cusps</a>. Here the automorphy factor $j(\gamma, z)$ is given by
\[
j(\gamma, z) = \theta(\gamma z)/\theta(z),
\]
where $\theta$ denotes the classical theta function. This space is denoted by $M_{k/2}(N)$, and the subspace of <a knowl="lmfdb/mf.elliptic.cusp_form">cusp forms</a> is denoted by $S_{k/2}(N)$.

These modular forms are related with integral weight modular forms through the <a knowl="lmfdb/mf.elliptic.shimura_correspondence">Shimura correspondence</a>. In terms of this correspondence, the space of cusp forms can be decomposed according to the <a knowl="lmfdb/mf.half_integral_weight.shimura_decomposition">mf.half_integral_weight.shimura_decomposition</a>.
