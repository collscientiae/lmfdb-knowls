title: Sign of an L-function
authors:
    swisherh
    gauss
    DavidFarmer

The **sign** of an <a knowl="lmfdb/lfunction">L-function</a> is the complex number $\varepsilon$ occurring in its <a knowl="lmfdb/lfunction.functional_equation">functional equation</a>

\[
\Lambda(s) := N^{s/2}
\prod_{j=1}^J \Gamma_{\mathbb R}(s+\mu_j) \prod_{k=1}^K \Gamma_{\mathbb C}(s+\nu_k)
\cdot L(s) = \varepsilon \overline{\Lambda}(1-s).
\]

It appears as the fourth component of the <a knowl="lmfdb/lfunction.selbergdata">Selberg data</a> of L.

If all of the coefficients of the Dirichlet series defining $L(s)$ are real, then necessarily
$ \varepsilon = \pm 1 $.  If the coefficients are real and $ \varepsilon = - 1 $,
then $ L(1/2)=0 $.
