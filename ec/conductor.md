title: Conductor of an elliptic curve
authors:
    cremona
    akoutsianas

The conductor of an elliptic curve $E$ defined over a number field $K$ is an ideal of the ring of integers of $K$ which is only divisible by the prime ideals of bad reduction and no others.  It is defined as
$$
    \mathfrak{n} = \prod_{\mathfrak{p}}\mathfrak{p}^{e_{\mathfrak{p}}}
$$
where the exponent $e_{\mathfrak{p}}$ is 

- $e_{\mathfrak{p}}=1$ if $E$ has multiplicative reduction at $\mathfrak{p}$,

- $e_{\mathfrak{p}}=2$ if $E$ has additive reduction at $\mathfrak{p}$ and $\mathfrak{p}$ does not lie above either $2$ or $3$, and

- $2\leq e_{\mathfrak{p}}\leq 2+6v_{\mathfrak{p}}(2)+3v_{\mathfrak{p}}(3)$, where $v_{\mathfrak{p}}$ is the valuation at $\mathfrak{p}$, if $E$ has additive reduction and $\mathfrak{p}$ lies above $2$ or $3$.

For the precise recipe for the exponent for primes above $2$ and $3$ see a text on elliptic curves.
