title: Shimura correspondence
authors:
    nsirolli

Let $k$ be an odd integer, and let $N$ a positive integer divisible by $4$. Let $\chi$ be a <a knowl="lmfdb/character.dirichlet">character</a> modulo $N$. Let $t$ be a square-free integer. The **Shimura correspondence** is the linear map $Sh_t:S_{k/2}(N, \chi)\to S_{k-1}(N/2, \chi^2)$ defined by the equation
\[
L(s, Sh_t(g)) = L(\chi_t, s+1-\lambda) \cdot \sum_{n\geq1} a_{tn^2} n^{-s},
\]
where

- $\lambda=(k-1)/2$.
- $\chi_t$ is the character given by $\chi_t(m) = \chi(m) \left(\frac{-1}{m}\right) \left(\frac{t}{m}\right)$.
- $g(z) = \sum_{n\geq1} a_n q^n$ is the $q$-expansion of $g$.


This map is Hecke linear. If $k\geq5$, it takes cusp forms to cusp forms.
