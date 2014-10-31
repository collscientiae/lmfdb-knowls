title: Root number of a local field
authors:
    john.jones

For a finite extension $K/\mathbb{Q}_p$, we give the **local root number**, or local sign, $\epsilon(K)  \in \{1,i,-1,-i\}$.

We start with a general description where we allow $p=\infty$, writing
$\Q_\infty = \R$.
Local root numbers, $\epsilon(\rho) \in \C^\times$, are defined for representations
$\rho : \mathrm{Gal}(\overline{\Q}_p/\Q_p)\rightarrow \GL_n(\C)$.  They
have absolute value $1$,
are multiplicative in the sense that $\epsilon(\rho_1 \oplus
\rho_2) = \epsilon(\rho_1)
\epsilon(\rho_2)$, and for $p \neq \infty$, 
any unramified representation has root number $1$.
The root number for the trivial and sign characters of $\mathrm{Gal}(\C/\R)$ are 
$1$ and $-i$ respectively.  Finally,
if $\rho : \mathrm{Gal}(\overline{\Q}/\Q) \rightarrow \GL_n(\C)$ is
a global representation whose restrictions to decomposition groups are
denoted by $\rho_p$, the global root number 
$\epsilon(\rho)$ equals the product of local root numbers
$\prod \epsilon(\rho_p)$, and $\epsilon(\rho)$
figures into the functional equation of the Artin $L$-function $L(\rho,s)$.

If $K$ is an $n$-dimensional $p$-adic algebra then 
$\mathrm{Gal}(\overline{\Q}_p/\Q_p)$ acts on the set of its $n$ 
embeddings into $\overline{\Q}_p$.  One thus has a 
representation $\rho_K :   \mathrm{Gal}(\overline{\Q}_p/\Q_p) \rightarrow S_n \subset \GL_n(\C)$.  For a local field $K$, we give the corresponding 
root number   $\epsilon(K) := \epsilon(\rho_K)$.  These particular root numbers 
play a central role in Galois embedding problems.
Finally, we note that for a global number field $K$, the global root number $\epsilon(K) = \prod \epsilon(K_p)$ is always $1$.
