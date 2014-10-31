title: Dirichlet character
authors:
    pdehaye
    conrey
    gauss
    malderso
    jbeineke
    john.jones
    DavidFarmer

A **Dirichlet character** is a function \(\chi: \Z\to \C\) together with a positive integer $q$, called the **modulus** of the character, such that $\chi$ is completely multiplicative, i.e. $\chi(mn)=\chi(m)\chi(n)$ for all integers $m$ and $n$, and $\chi$ is periodic modulo $q$, i.e. $\chi(n+q)=\chi(n)$ for all $n$. If $(n,q)>1$ then $\chi(n)=0$, whereas if $(n,q)=1$, then $\chi(n)$ is a root of unity. The character is **primitive** if its 
<a knowl="lmfdb/character.dirichlet.conductor">conductor</a>
is equal to its modulus.

For this database, we use the notation $\chi_{q}(n,·)$ for Dirichlet characters, where $q$ is the modulus, and the index $n$ is such that $(q, n) = 1$.  In the case where $q$ is odd, write $q = p_1^{e_1} p_2^{e_2} \cdots p_k^{e_k}$.  Let $g_i$ be a primitive root modulo $p_i^e$ for every $e > 0$.  If $n \equiv g_i^{a_i} $ mod $p_i^{e_i}$ and $m \equiv g_i^{b_i} $ mod $p_i^{e_i}$ for $i = 1, 2, \ldots, k$, then define 
$$\chi_q(n, m) = \exp\left(2\pi i \sum_{i=1}^k \frac{a_i b_i}{\phi(p_i^{e_i})} \right).$$
