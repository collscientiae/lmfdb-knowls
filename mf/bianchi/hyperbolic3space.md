title: Hyperbolic 3-space
authors:
    Haluk

Hyperbolic 3-space $\mathcal{H}_3$ is the unique connected, simply connected Riemannian manifold of dimension 3 with constant sectional curvature $-1$.  A standard model for $\mathcal{H}_3$ is the upper half space model 
$$\{ (x,y) \in \C \times \R \mid y>0 \} = \{ (x_1,x_2,y) \in \R^3 \mid y>0 \}  $$
with the metric coming from the line element
$$ds^2 = \dfrac{dx_1^2+dx_2^2+dy^2}{y^2}$$
under which the distance $d(P,P')$ between two points $P=(x_1,x_2,y)$,$P'=(x'_1,x'_2,y')$ is given by
$$\cosh d(P,P')=1+ \dfrac{(x_1-x'_1)^2+(x_2-x'_2)^2+(y-y')^2}{2yy'}.$$

The orientation-preserving isometries of $\mathcal{H}_3$ can be identified with the group $\textrm{PSL}_2(\mathbb{C}) \simeq \textrm{PGL}_2(\mathbb{C})$. The action on $\mathcal{H}_3$ is given as 
$$\begin{pmatrix} a & b \\ c&d \end{pmatrix} \cdot z = 
\Biggl ( \frac{(ax+b)\overline{(cx+d)}+a\bar{c}y^2}{|cx+d|^2+|c|^2y^2},\frac{y}{|cx+d|^2+|c|^2y^2} \Biggr )$$
where $z=(x,y) \in \mathcal{H}_3$. 

It is computationally convenient to regard $\mathcal{H}_3$ inside the Hamiltonians $\mathbb{H}$. We embed $\mathcal{H}_3$ into $\mathbb{H}$ via $(x_1,x_2,y) \mapsto (x_1,x_2,y,0).$ In other words, $(x,y) \mapsto x+y j$. In particular, the element $j \in \mathbb{H}$ corresponds to $(0,0,1) \in \mathbb{R}^3$. Then the action of 
$\textrm{PSL}_2(\mathbb{C})$ on $\mathcal{H}_3$ takes the familiar form
$$\begin{pmatrix} a & b \\ c&d \end{pmatrix} \cdot z = (az+b)(cz+d)^{-1} $$
where the inverse of $cz+d$ is taken inside the skew-field $\mathbb{H}$. 

To see this transition, consider $\mathbb{H}$  as a subalgebra of $\mathbb{H} \otimes_\mathbb{R} \mathbb{C} \simeq M_2(\mathbb{C})$ as follows
$$\mathbb{H} \hookrightarrow M_2(\mathbb{C}), \ \ \ x+yj \mapsto \begin{pmatrix} x & -y \\ \bar{y} & \bar{x}\end{pmatrix}.$$
In particular,  if $x \in \C$, we have $x \mapsto (\begin{smallmatrix} x & 0 \\ 0 & \bar{x}\end{smallmatrix})$. This embedding respects the ring operations of $\mathbb{H}$. It is now trivial to verify the equivalence between the two descriptions of the action of $\textrm{PSL}_2(\mathbb{C})$ on $\mathcal{H}_3$ that we gave above when we consider this matrix representation of 
$\mathcal{H}_3 \subset \mathbb{H}$.
