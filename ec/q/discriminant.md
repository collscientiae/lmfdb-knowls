title: Discriminant of an elliptic curve over $\mathbb Q$
authors:
    dkhuynhms
    gauss
    jbeineke

The **discriminant** $\Delta$ of an <a knowl="lmfdb/ec">elliptic curve</a> $E$ defined over $\mathbb{Q}$ is a nonzero integer divisible exactly by the primes of bad reduction.
If the <a knowl="lmfdb/ec.q.minimal_weierstrass_equation">minimal Weierstrass equation</a> of $E$ is \[y^2+a_1xy+a_3y=x^3+a_2x^2+a_4x+a_6,\] then $\Delta$ is given by a polynomial expression in $a_1,\dots,a_6$. Namely,
\[\Delta=-b_2^2b_8 - 8 b_4^3 -27 b_6 ^2 + 9 b_2 b_4 b_6\] where 
$$\begin{eqnarray*}
b_2 &=& a_1^2 + 4 a_2\\ 
b_4 &=& 2a_4 + a_1 a_3\\ 
b_6 &=& a_3^2 + 4 a_6 \\
b_8 & =& a_1^2 a_6 + 4 a_2 a_6 - a_1 a_3 a_4 + a_2 a_3^2 - a_4^2.  \end{eqnarray*}$$
