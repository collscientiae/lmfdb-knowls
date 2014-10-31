title: Maass form on GL2(R)
authors:
    fredstro
    swisherh
    gauss
    jbeineke
    john.jones

Maass forms of weight $0$
------------------
A **Maass form** on a subgroup \(\Gamma\) of \(\GL_{2}(\R)\)
is a smooth, square-integrable, automorphic eigenfunction of the <a knowl="lmfdb/mf.maass.mwf.laplacian">Laplace-Beltrami operator</a> $\Delta$. In other words, 
$$f\in C^\infty(\mathcal{H}),\quad f\in L^2(\Gamma\backslash{\cal H}),\quad f(\gamma z)=f(z)\ \forall\gamma\in\Gamma,\quad (\Delta+\lambda)f(z)=0 \textrm{ for some } \lambda \in \C.$$

Maass forms of weight $k$
------------------

A Maass form $f$ of weight $k$ and <a knowl="lmfdb/mf.multipliersystem">multiplier system</a> $v$ on a group $\Gamma$ is a smooth function $f:\mathcal{H} \rightarrow\C$ with the following properties:

1. it transforms according to a unitary weight \( k\) slash-action:
 $ f|[\gamma,k]( z) = v(\gamma) f(z)$ for all $\gamma \in \Gamma$ where 
\( f|[\gamma,k]( z) = \exp(-ik\mathrm{Arg}(c z+d)) f(\gamma z)\) for $\gamma=\left(\matrix{a & b \\ c & d }\right)$

2. it is an eigenfunction of the corresponding weight $k$ Laplacian 
\( \Delta_k = y^2\left( \frac{\partial^2}{\partial x^2}+\frac{\partial^2}{\partial y^2}\right) - iky\frac{\partial}{\partial x} \)

If the level is equal to one the only possible multiplier systems are given by the Dedekind eta function. A compatible multiplier system for weight $k\in \R$ is given by 

\[ v(A) = v_{\eta}^{2k}:=\eta(Az)^{2k}/\eta(z)^{2k} \]

or one of its 6 conjugates. One can show that $v(A)$ is well-defined and independent of the point $z$ in the upper half-plane.


Remark:
-------
 One can also consider Maass forms transforming with the usual "holomorphic" weight $k$ slash-action. In this case the corresponding weight $k$ Laplacian will look slightly different: \( \Delta_k = y^2\left( \frac{\partial^2}{\partial x^2}+\frac{\partial^2}{\partial y^2}\right) - iky\left(\frac{\partial}{\partial x}+i\frac{\partial}{\partial y}\right). \)
This convention is usually used in the context of Harmonic weak Maass forms.




Keywords: #Maass #Laplacian
