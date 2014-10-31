title: Galois representation
authors:
    cremona

If $E$ is an <a knowl="lmfdb/ec.q">elliptic curve defined over $\Q$</a> and $m\ge2$ then the mod-$m$ Galois representation attached to $E$ is the map
\[
    \rho_{E,m}: \Gal(\overline{\Q}/\Q) \to \Aut(E[m]),
\]
giving the action of the <a knowl="lmfdb/group.galois.absolute">absolute Galois group</a> of $\mathbb{Q}$ on the $m$-torsion subgroup $E[m]$.

By identifying the finite abelian group $E[m]$ with $(\Z/m\Z)^2$ we may identify $\Aut(E[m])$ with $\GL(2,\Z/m\Z)$ and hence view the representation as a map
\[
    \rho_{E,m}: \Gal(\overline{\Q}/\Q) \to \GL(2,\Z/m\Z),
\]
defined up to conjugation.  In the case where $m=p$ is prime we have
\[
    \rho_{E,p}: \Gal(\overline{\Q}/\Q) \to \GL(2,\F_p).
\]
