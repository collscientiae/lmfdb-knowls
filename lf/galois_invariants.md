title: Galois invariants of a local field
authors:
    john.jones

Some invariants of $K^{gal}$, the Galois closure of a local field $K$ starts with the <a knowl="lmfdb/nf.galois_group">Galois group</a> $G=\textrm{Gal}(K^{gal}/\mathbb{Q}_p)$.  Most of the remaining invariants relate to the filtration on $G$ by higher ramification groups.

Let $G^i$ be the $i$th higher ramification group in upper numbering from Serre's <i>Local Fields</i>.  They form a descending filtration of normal subgroups where $i$ is a continuous parameter, $i\geq -1$.  Let $G^{(j)} = G^{j-1}$, and $G^{(j+)} = \cap_{\epsilon>0} G^{(j+\epsilon)}$.  Then

- $G^{(0)}=G$.

- $G^{(1)}$ is the inertia subgroup of $G$, i.e., the kernel of the natural map from $G$ to the Galois group of the residue field.

- the fixed field of $G^{(1)}$ is the maximum unramified subfield of $K^{gal}/\mathbb{Q}_p$, which we denote by $K^{unram}$.  The degree $[K^{unram}:\mathbb{Q}_p]$ is the unramified degree for $K^{gal}/\mathbb{Q}_p$.  The extension $K^{gal}/K^{unram}$ is totally ramified.

- the group $G^{(1)}/G^{(1+)}$ is cyclic of order prime to $p$.  Its order is the tame degree for $K^{gal}/\mathbb{Q}_p$ as it is the degree of the largest tamely totally ramified subextension.  

- The group $G^{(1+)}$ is a $p$-group.  Values of $s>1$ giving jumps in the filtration $G^{(s)}\neq G^{(s+)}$ are wild slopes.  We repeat a slope $m$ times if $p^m =[G^{(s)} : G^{(s+)}]$, and then list the wild slopes in non-decreasing order.

- The GMS, or Galois Mean Slope, is the mean slope for $K^{gal}/\mathbb{Q}_p$.
