title: Symmetric power of an L-function
authors:
    gauss
    rishi
    john.jones

Let $L(s)$ be an L-function given by an Euler product
    \[
    L(s)= \prod_{p\not\in S} \prod_{j=1}^r \left (1-
\frac{\alpha_j}{p^s}\right)^{-1} \times \prod_{p \in S} L_p(s),
   \]
where $S$ is a finite set of primes.  The  symmetric $n$-th power of $L(s)$ is an L-function given by an Euler product
    \[
    L(s,\mathrm{sym}^n) = \prod_{p\not\in S}\prod_{\substack{\mathrm{degree}-n\\ \mathrm{monomials}}} \left( 1-
\frac{m(\alpha_1,\dotsc,\alpha_r)}{p^s} \right)^{-1} \times
\prod_{p\in S} L_p(s,\mathrm{sym}^n).
    \]
The Euler factors at the primes $p\in S$ (the  "bad" primes) are computed via a more complicated recipe which involves a non-trivial amount of information about the underlying object.   The degree of an Euler factor at one of the bad primes will be smaller than the degree of the Euler factors outside the set $S.$
