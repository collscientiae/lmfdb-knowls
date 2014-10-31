title: j-invariant
authors:
    dkhuynhms
    gauss

The **$j$-invariant** of an <a knowl="lmfdb/ec">elliptic curve</a> $E$ defined over $\mathbb{Q}$ is an invariant of the isomorphism class of $E$ over  $\bar{\mathbb{Q}}.$ 
If the <a knowl="lmfdb/ec.q.minimal_weierstrass_equation">minimal Weierstrass equation</a> of $E$ is \[y^2+a_1xy+a_3y=x^3+a_2x^2+a_4x+a_6,\] then its $j$-invariant is given by 
\[j= \frac{c_4^3}{\Delta}\] where 
\[\begin{eqnarray*}
b_2 &=& a_1^2 + 4 a_2\\ 
b_4 &=& 2a_4 + a_1 a_3\\ 
b_6 &=& a_3^2 + 4 a_6 \\
b_8 & =& a_1^2 a_6 + 4 a_2 a_6 - a_1 a_3 a_4 + a_2 a_3^2 - a_4^2\\
c_4&=& b_2^2 - 24b_4 \end{eqnarray*}\]and \[\Delta=-b_2^2b_8 - 8 b_4^3 -27 b_6 ^2 + 9 b_2 b_4 b_6\]
is the <a knowl="lmfdb/ec.q.discriminant">discriminant</a> of $E.$
