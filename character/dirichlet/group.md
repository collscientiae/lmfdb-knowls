title: Dirichlet character group
authors:
    john.jones

If $G$ is a finite abelian group, its *dual group* is the set of group homomorphisms
\[ \hat G = \{\chi: G\to \mathbb{C}^*\}.\]
The elements of $\hat G$ are *characters* of $G$, and form a group under multiplication:
\[ (\chi_1 \chi_2)(g) := \chi_1(g) \cdot \chi_2(g).\]

If $K$ is a number field which is Galois over $\mathbb{Q}$ with $G=\textrm{Gal}(K/\mathbb{Q})$ an abelian group, then by the Kronecker-Weber theorem, $K\subseteq \mathbb{Q}(\zeta_n)$ where $\zeta_n$ is a primitive root of unity for some $n$.  The characters of $G$ give characters of $\textrm{Gal}(\mathbb{Q}(\zeta_n)/\mathbb{Q})$ by composition with the natural surjection $\textrm{Gal}(\mathbb{Q}(\zeta_n)/\mathbb{Q}) \to \textrm{Gal}(K/\mathbb{Q})$.  Identifying $\textrm{Gal}(\mathbb{Q}(\zeta_n)/\mathbb{Q})$ with $(\mathbb{Z}/n\mathbb{Z})^*$, we can then identify elements of $\hat G$ with 
<a knowl="lmfdb/character.dirichlet">Dirichlet characters</a>.
