title: Dirichlet L-function
authors:
    jbeineke
    swisherh

A **Dirichlet L-function** is given by ${\displaystyle L(s, \chi)=\sum_{n=1}^\infty \frac {\chi(n)}{n^s}}$ for Re$(s) >1$, where $\chi$ is a <a knowl="lmfdb/character.dirichlet">Dirichlet character</a>.  

These L-functions can be meromorphically continued to the complex plane and have <a knowl="lmfdb/lfunction.euler_product">Euler product</a>  ${\displaystyle L(s, \chi)= \prod_p (1 - \chi(p) p^{-s} )^{-1}}$, where the product is over all primes $p$.

The <a knowl="lmfdb/lfunction.functional_equation">functional equation</a> takes the form $\Lambda(s,\chi) = q^{s/2} \Gamma_{\mathbb R} (s+a) L(s,\chi) = \varepsilon_\chi \overline{\Lambda}(1-s)$, where $q$ is the <a knowl="lmfdb/character.dirichlet.conductor">conductor</a> of $\chi$.

These L-functions were introduced by <a knowl="lmfdb/bio.dirichlet">Dirichlet</a> in the mid-1800s as a tool to study prime numbers in arithmetic progressions.  
