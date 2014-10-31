title: Field cut out by a Dirichlet character
authors:
    john.jones

Let $\chi:\mathbb{Z}\to \mathbb{C}$ be a <a knowl="lmfdb/character.dirichlet">Dirichlet character</a> with <a knowl="lmfdb/character.dirichlet.modulus">modulus</a> $q$.  Then $\chi$ restricts to a homomorphism $\chi:(\mathbb{Z}/q\mathbb{Z})^*\to \mathbb{C}^*$.  Identifying $(\mathbb{Z}/q\mathbb{Z})^*$ with $\textrm{Gal}(\mathbb{Q}(\zeta_q)/\mathbb{Q})$ by $a\mapsto \sigma_a$ with $\sigma_a(\zeta_n)=\zeta_n^a$, we then identify $\ker(\chi)$ with a subgroup of $\textrm{Gal}(\mathbb{Q}(\zeta_q)/\mathbb{Q})$.
By the Galois correspondence, its fixed field $\mathbb{Q}(\zeta_q)^{\ker(\chi)}$ is a subfield of $\mathbb{Q}(\zeta_q)$ whose Galois group is isomorphic to $\textrm{Im}(\chi)$, which is cyclic of order $n$ where $n$ is the <a knowl="lmfdb/character.dirichlet.order">order</a> of $\chi$.
