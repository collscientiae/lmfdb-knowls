title: Euler product of an L-function
authors:
    StefanLemurell
    conrey
    jbeineke
    DavidFarmer

It is expected that the **Euler product** of an <a knowl="lmfdb/lfunction">L-function</a> of <a knowl="lmfdb/lfunction.degree">degree</a> $d$ and <a knowl="lmfdb/lfunction.level">level</a> $N$ can be written as
$$L(s)=\prod_p L_p(s)$$ 
where for  $p\nmid N$
$$L_p(s)=\prod_{n=1}^d  \left( 1-\frac{\alpha_{n}(p)}{p^s}\right)^{-1} \text{ with } |\alpha_{n}(p)|=1$$
and 
for $p\mid N$, 
$$L_p(s)=\prod_{n=1}^{d_p}\left( 1-\frac{\beta_{n}(p)}{p^s}\right)^{-1} \text{ where } d_p<d \text{ and }  |\beta_n(p)|\le 1.$$
