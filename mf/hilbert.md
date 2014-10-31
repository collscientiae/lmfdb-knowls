title: Hilbert modular form
authors:
    swisherh
    cremona
    lassina
    john.jones
    jvoight

Let $F$ be a <a knowl="lmfdb/nf.totally_real">totally real</a> <a knowl="lmfdb/nf">number field</a> $F$ of <a knowl="lmfdb/nf.degree">degree</a> $n>1$ and
strict <a knowl="lmfdb/nf.class_number">class number</a> $1$. Let $\sigma_1,\ldots,\sigma_n$ be the real embeddings of $F$ into $\R$. Let $k$ be a positive integer, and let $\mathfrak{N}$ be a nonzero ideal of the <a knowl="lmfdb/nf.ring_of_integers">ring of integers</a> $\Z_F$ of $F$. Write $\alpha\gg 0$ if $\alpha$ is <a knowl="lmfdb/nf.totally_positive">totally positive</a>. 

A **Hilbert modular form** of parallel weight $k$ and level $\mathfrak{N}$ is a holomorphic function $f:\mathcal{H}^n\rightarrow \C$ such that for $z=(z_1\ldots,z_n)\in\mathcal{H}^n$ and all 
\[ \gamma\in\Gamma_0(\mathfrak{N}) = \left\{\gamma=\begin{pmatrix} a & b \\ c & d \end{pmatrix} \in \GL_2(\Z_F) : c \in \mathfrak{N} \text{ and } \det(\gamma)\gg 0\right\}, \] 
we have
\[
f(\gamma z)=f\left(\frac{a_1z_1+b_1}{c_1z_1+d_1}, \ldots, \frac{a_nz_n+b_n}{c_nz_n+d_n}\right)=\prod_{i=1}^n\left( \frac{(c_iz_i+d_i)^{k}}{\det{\gamma_i}^{k-1}}\right)f(z),
\]
where $\gamma_i=\sigma_i(\gamma)=\begin{pmatrix}a_i&b_i\\c_i&d_i\end{pmatrix}$. 

A **Hilbert cusp form** is a Hilbert modular form that vanishes at the cusps. 
