title: Functional equation of an L-function
authors:
    pdehaye
    gauss
    jbeineke
    DavidFarmer
    conrey
    swisherh
    rfurman

All known <a knowl="lmfdb/lfunction">analytic L-functions</a> have a **functional equation** that can be written in the form
\[
\Lambda(s) := N^{s/2}
\prod_{j=1}^J \Gamma_{\mathbb R}(s+\mu_j) \prod_{k=1}^K \Gamma_{\mathbb C}(s+\nu_k)
\cdot L(s) = \varepsilon \overline{\Lambda}(1-s),
\]
where $N$ is an integer, <a knowl="lmfdb/specialfunction.gammarandc">$\Gamma_{\mathbb R}$ and $\Gamma_{\mathbb C}$</a> are defined in terms of the <a knowl="lmfdb/specialfunction.gamma">$\Gamma$-function,</a> $\mathrm{Re}(\mu_j) = 0 \ \mathrm{or} \ 1$ (assuming Selberg's eigenvalue conjecture), and $\mathrm{Re}(\nu_k)$ is a positive integer
or half-integer, and
\[
2\sum \mu_j + \sum \nu_k \ \ \ \ \mbox{is real}.
\]
With those restrictions on the <a knowl="lmfdb/lfunction.spectral_parameters">spectral parameters</a>, the
data in the functional equation is specified uniquely.  The integer $d = J + 2 K$
is the <a knowl="lmfdb/lfunction.degree">degree</a> of the L-function. The integer $N$ is  the <a knowl="lmfdb/lfunction.level">level</a>
of the L-function.  The pair $[J,K]$ is the <a knowl="lmfdb/lfunction.signature">signature</a> of the L-function.  The parameters
in the functional equation can be used to make up the 4-tuple called the <a knowl="lmfdb/lfunction.selbergdata">Selberg data</a>.
 

The <a knowl="lmfdb/lfunction.selberg_class.axioms">axioms</a> of the <a knowl="lmfdb/lfunction.selberg_class">Selberg class</a> are less restrictive than
given above.

Note that the functional equation above has the central point at $s=1/2$, and relates $s\leftrightarrow 1-s$.

For many L-functions there is another normalization which is natural. The corresponding functional equation relates $s\leftrightarrow w+1-s$ for some positive integer $w$; the central point is at $s=(w+1)/2$, and the arithmetically normalized Dirichlet coefficients $a_n n^{w/2}$ are algebraic integers.

More information is available about the <a knowl="lmfdb/lfunction.taxonomy">properties of analytic L-functions</a>.
