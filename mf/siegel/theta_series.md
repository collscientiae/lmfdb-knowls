title: Siegel theta series and theta series with pluriharmonics
authors:
    davidyuen
    DavidFarmer

Given a positive definite quadratic $m\times m$
positive definite even quadratic form $Q$,
and given a degree $g$,
define
$$\vartheta_Q^{(g)}(\Omega)
=
\sum_{X\in\Bbb Z^{m \times g}}
\exp(\pi i N' Q N \Omega )
$$

If $m$ is a multiple of 4,
this is a Siegel modular form of degree $g$
of weight $m/2$
with respect to the subgroup $\Gamma_0(\ell)$
where $\ell$ is such that $\ell Q^{-1}$ is an even quadratic form.

We say $P$ is pluriharmonic (spherical function) in the matrix variable
$X=(x_{r,s})$ for $1\le r\le m$, $1\le s\le g$,
 if
<ul>
<li>for each $1\le i,j\le n$, we have $\displaystyle{\sum_{t=1}^g\frac{\partial^2 P}{\partial_{i,t}\partial_{j,t}}=0}$</li>
</ul>
Define the theta series with pluriharmonic polynomial $P$ homogeneous of degree $\nu$
to be
$$\vartheta_{Q,P}^{(g)}(\Omega)=
\sum_{X\in\Bbb Z^{m \times g}}
P(N) \exp(\pi i N' Q N \Omega )
$$

If $m$ is a multiple of 4,
this is a Siegel cusp form of weight $m/2+\nu$ in degree $g$ 
with respect to the subgroup $\Gamma_0(\ell)$.

When $m$ is not a multiple of $4$, one gets a Siegel modular form with a character.
