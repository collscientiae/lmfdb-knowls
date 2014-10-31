title: Selberg class axioms
authors:
    conrey
    roed
    swisherh
    john.jones

The ** Selberg axioms** for $F(s)=\sum_{n=1}^\infty \frac{a_n}{n^s}$ in the <a knowl="lmfdb/lfunction.selberg_class">Selberg class</a> are:
<ol>
<li>   Analyticity: $(s-1)^mF(s)$ is an entire function of
finite order for some non-negative integer $m$
<li> Ramanujan Hypothesis: $a_n = O_{\epsilon}(n^\epsilon)$ for any fixed $\epsilon>0$
<li>  <a knowl="lmfdb/lfunction.functional_equation">Functional equation</a>: there is a function $\gamma_F(s)$ of the
form
$$\gamma_F(s)=\epsilon Q^s \prod_{i=1}^k\Gamma(\lambda_is+\mu_i)$$
where $|\epsilon|=1$, $Q>0$, $\lambda_i>0$, and Re$(\mu_i)\ge 0$
such that $$\Lambda(s)=\gamma_F(s)F(s)$$
satisfies
$$\Lambda(s)=\overline{\Lambda}(1-s)$$
where $\overline{\Lambda}(s)=\overline{\Lambda(\overline{s})}$.</li>
<li>  <a knowl="lmfdb/lfunction.euler_product">Euler product</a>: $a_1=1$,
 and $$\log F(s)=\sum_{n=1}^\infty \frac{b_n}{n^s}$$
where $b_n=0$ unless $n$ is a positive power of a prime
and $b_n\ll n^\theta$ for some $\theta<1/2$.</li>
</ol>
