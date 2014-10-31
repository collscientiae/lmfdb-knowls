title: Level of an L-function
authors:
    pdehaye
    DavidFarmer
    conrey
    jbeineke
    swisherh

The **level** of an <a knowl="lmfdb/lfunction">L-function</a> is the integer $N$  occurring in its <a knowl="lmfdb/lfunction.functional_equation">functional equation</a>

\[
\Lambda(s) := N^{s/2}
\prod_{j=1}^J \Gamma_{\mathbb R}(s+\mu_j) \prod_{k=1}^K \Gamma_{\mathbb C}(s+\nu_k)
\cdot L(s) = \varepsilon \overline{\Lambda}(1-s).
\]


The level of an analytic <a knowl="lmfdb/lfunction">L-function</a> is the second component in the <a knowl="lmfdb/lfunction.selbergdata">Selberg data</a>. For a <a knowl="lmfdb/lfunction.dirichlet">Dirichlet L-function</a>
 associated with a primitive <a knowl="lmfdb/character.dirichlet">Dirichlet character</a>, the level of the L-function is the same as the <a knowl="lmfdb/character.dirichlet.conductor">conductor</a> of the character. For a primitive L-function associated with a <a knowl="lmfdb/mf.elliptic.cusp_form">cusp form</a> $\phi$ on $GL(2)/\mathbb Q$, the level of the L-function is the same as the level of $\phi$.
