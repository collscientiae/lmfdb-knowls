title: Riemann zeta-function
authors:
    DavidFarmer
    conrey
    gauss

The **[Riemann zeta-function](http://lmfdb.org/L/Riemann/)** is defined by
$$\zeta(s)=\sum_{n=1}^\infty \frac 1{n^s}$$
for $s=\sigma+it$ with $\sigma>1$. Euler showed that
$$\zeta(s)=\prod_p (1-1/p^s)^{-1},$$
known today as the Euler product, for $s$ a real number with $s>1$, a fact that connects the study of $\zeta(s)$ with the prime numbers.
 Riemann, in 1859,  was the first to consider $\zeta(s)$  as a function of a complex variable.  He proved that $\zeta(s)$ has an analytic continuation to the whole complex plane apart from a simple pole at $s=1$ with residue 1. Riemann proved a remarkable functional equation. He showed that 
$$\xi(s):=\frac 12 s (s-1) \pi^{-s/2} \Gamma(s/2) \zeta(s) $$
is an entire function of order 1 which satisfies 
$$\xi(s)=\xi(1-s).$$
Riemann showed that the distribution of prime numbers depends on the location of the zeros of the Riemann zeta-function which, by the Euler product and functional equation, are all in the critical strip $0\le \sigma \le 1$. Riemann showed that the number $N(T)$ of zeros of 
$\zeta(s)$ in the critical strip with ordinates at most $T$ satisfies
 $$N(T)=\frac{T}{2\pi} \log\frac{T}{2\pi e} +O(\log T).$$ 
He calculated the first few zeros and verified that they are on the critical line $\sigma=1/2$ and then made his famous conjecture, today known as the Riemann Hypothesis, that all of the zeros are on the critical line. In 1896 Hadamard and de la Vallee Poussin independently proved that $\zeta(s)$ has no zeros on the boundary of the critical strip, i.e. all of the zeros are in the open strip $0< \sigma < 1$,
and in doing so proved the Prime Number Theorem, that the number of primes less than a large number $x$ is asymptotic to $\frac{x}{\log x}$. 

Today we know that the first 10 trillion zeros of $\zeta(s)$ are all on the critical line and that at least 41% of all of the complex zeros are on the critical line.
