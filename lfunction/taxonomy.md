title: Taxonomy of L-functions
authors:
    DavidFarmer

Taxonomy of L-functions
=======================

One can consider $L$-functions as autonomous objects, not necessarily
arising from another more basic object.  From that point of view it
is natural to develop a taxonomy of $L$-functions, where
only the properties of the $L$-function are used for the classification.

The most obvious invariant of an $L$-function is its \emph{degree}.
After the degree, it is not immediately obvious which properties
of the $L$-function should be considered next, but we propose the
following as a reasonable scheme:

Note: some of the names could be better.  And the order is not
canonical.

0) Degree.

The non-negative integer $d=J+2K$, where $J$ and $K$
refer respectively to the number of $\Gamma_\R$ and
$\Gamma\C$ factors in the functional equation.
Recall that the $L$-function axioms determine $J$ and $K$
uniquely.

1) Signature.

The pair $(J,K)$.

1.5) $\Gamma$-data

The pair $(\{\mu_1,...,\mu_J\}, \{\nu_1,...,\nu_K\})$, where at this
point we may wish to think of the $\mu_j$ and $\nu_k$ as depending on
a parameter.  For example, the two main classes of degree 2
$L$-functions have:
$$
(\{i\lambda,-i\lambda\},\{\})
\ \ \ \ \ \ \ \ \
or
\ \ \ \ \ \ \ \ \
(\{\},\{\frac{k-1}{2}\}),
$$
where $\lambda$ is a positive real number and $k$ is an integer.

2) Is the $L$-function algebraic?

We call an $L$-function \emph{algebraic} if its Dirichlet
coefficients are algebraic numbers.  This, conjecturally,
is equivalent to each of:

a) $\mu_j$ and $\nu_k$ are real

b) The $L$-function is the $L$-function of a Galois representation.

c) The $L$-function is motivic

d) There exists an number field $K/\Q$,
called the \emph{field of coefficients},
and a integer $w$, called the \emph{motivic weight} of the $L$-function,
such that $a_n n^{w/2}$ is in integer of $K$ for all $n$.
(Note that $w$ is chosen to be the minimal integer with this property.)
(Note also that, conjecturally, $w=\min\{0,\max\{\nu_k\}\}$.
In the arithmetic normalization, the functional equation relates $s$
to $w+1-s$.)
(Note that for holomorphic $GL(2)$ cusp forms, motivic weight
is one less than the "classical" weight. (terminology?)
For Siegel modular forms, the "classical" weight has yet
another relationship to the motivic weight.)

2') The motivic weight

2'') The field of coefficients

3) Level.

The non-negative integer $N$ appearing in the functional equation.

Note: Once the level and the specific numbers in the $\Gamma$-factors
have been specified, then (conjecturally) there are only finitely many
$L$-functions possible.

4) Central character.

The Euler product has the form
$$
L(s) = \prod_p F_p(p^{-s})
$$
where
$$
F_p(x) = 1+a_p x + \cdots + (-1)^d \chi(p)  x^d.
$$
The character $\chi$, which is a Dirichlet character mod~$N$,
is called the \emph{central character}
of the $L$-function.

If $p$ is a good prime, then the roots of $F_p$ are
called the \emph{Satake paramaters at $p$} for the
$L$-funciton.

Note: if $L(s)=L(s,f)$ for some object $f$, then $f$ may have
its own Satake parameters, which in general are diferent from the
Satake parameters of the $L$-function.  (This has to be the case,
because $f$ probably has infinitely many $L$-functions associated
to it, and each $L$-function has different Satake parameters.)


5) Sign.

The parameter $\varepsilon$ appearing in the functional equation.
Also known as the ``root number.''

The above classification exhausts the parameters in the functional
equation
and the Euler product,
but there are further refinements based on the distribution
of Dirichlet coefficients.

6) Self-dual?

Are the Dirichlet coefficients real?

7) Sato-Tate group

The Sato-Tate group of an $L$-function is a compact subgroup
of a classical matrix group whose eigenvalues under Haar measure have the
same distribution as the distribution of Satake parameters
of the $L$-function.  Further discussion below.

The Dirichlet coefficients $a_p$,...,$a_{p^{[d/2]}}$ have
a limiting distribution.  The first few moments of those
coefficients uniquely determine the distributions.
For example, when $d=2$ and $w\ge 1$ there are two possibilities:
$$
\langle |a_p|^2 \rangle = 1,
\ \ \ \ \
\langle |a_p|^4 \rangle = 2;
$$
and
$$
\langle |a_p|^2 \rangle = 1,
\ \ \ \ \
\langle |a_p|^4 \rangle = 3.
$$
The first possibility is commonly called "Sato-Tate" and
the second is commonly called "CM."
For $d=2$ and $w=0$ there are several more options.

Serre uses "Sato-Tate group" for the general case. See his
excellent book "Lectures on $N_X(p)$".

As the degree grows there are more possibilities: 55 in the case
of $d=4$, $w=1$.  Kedlaya and Sutherland have more than 30
examples arising from hyperelliptic curves.

Note: the above is not all accurate.  The two possibilities
listed for degree 2, weight 1, are for real coefficients
(i.e., self-dual $L$-functions), and the same may also be true
of the 55 possibilities for  $d=4$, $w=1$.

Note:  The first few coefficient moments determine the distribution
because there is a compact matrix group whose eigenvalues have
the same distribution as the Satake parameters.  That group is
the \emph{Sato-Tate group} of the $L$-function.  All of this
is conjectural.  (this may not be quite right, so please provide
corrections.)

Note: The Sato-Tate group determines which operations on the $L$-function
($sym^n$, for example) have poles.
