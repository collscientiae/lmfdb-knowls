title: Jacobi forms
authors:
    davidyuen
    john.jones

A Jacobi form (of full level) of weight $k$ and index $N$
is a holomorphic function $f:\mathcal{H}\times\C\to \C$
where $\mathcal{H}$ is the upper half plane that satisfies the following conditions.
<ul>
<li>For all $\left(\begin{smallmatrix}a&b\\c&d\end{smallmatrix}
\right)
\in SL(2,{\Bbb Z})$, we have
$$f\left(\frac{a\tau+b}{c\tau+d}, \frac{z}{c\tau+d}\right)= (c\tau+d)^k e^{2\pi i\, mcz^2 /(c\tau+d)} f(\tau,z)$$
</li>
<li>$f$ has a Fourier expansion
$$f(\tau,z)=\sum_{n,r:4nN-r^2\ge0} c(n,r) e^{2\pi i
(n\tau+r z)}.$$
</li>
</ul>
The space of Jacobi forms is denoted by $J_{k,N}$.
If furthermore, the Fourier expansion is over only those $n,r$
for which $4Nn-r^2>0$,
we say it is a Jacobi cusp form, and denote the space of Jacobi cusp forms by
$J_{k,N}^{\text{cusp}}$.
