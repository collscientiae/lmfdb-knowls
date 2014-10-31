title: Introduction/Tutorial
authors:
    schilly
    swisherh
    john.jones
    jbeineke
    DavidFarmer
    pdehaye

The simplest of all <a knowl="lmfdb/lfunction.definition">L-functions</a> is the <a knowl="lmfdb/lfunction.riemann">Riemann zeta function</a>, a
function whose analytic properties were first discovered by <a knowl="lmfdb/bio.riemann">Riemann</a> in
1859 in his attempts to find a formula for the number of primes
smaller than a given number $x$. It gives us a model for how to think
about other L-functions.

Let's begin by  taking a look at this prototype:
<a href="http://www.lmfdb.org/L/Riemann/" target="_blank">the Riemann zeta function homepage</a>.


The first thing we see is that the Riemann zeta function can be
defined as a special type of infinite series, called a <a knowl="lmfdb/lfunction.dirichlet_series">Dirichlet
series</a>:

$\zeta(s):=1+\frac1{2^s}+\frac1{3^s}+\frac1{4^s}+\cdots.$

This is the classical definition of $\zeta(s)$ and holds in the half
plane $Re(s)>1$.

All L-functions can be expressed as Dirichlet series. On this website
we normalize each Dirichlet series so
that it converges absolutely for  $ Re (s)>1$.

The page then exhibits the <a knowl="lmfdb/lfunction.functional_equation">functional equation</a>, an equation that
relates the values of this L-function on the left and on the right of
the line $ Re (s)= 1/2$. A key component of the functional equation is that it
involves <a knowl="lmfdb/specialfunction.gamma">Euler's Gamma function</a>, which is well known as a function
that interpolates factorials.
Again, this is typical of all L-functions: there is a functional
equation involving the product of the L-function and some
Gamma functions and relates the values at $s$ and $1-s$.  The "Selberg data" is a way of encoding the functional equation; details at the bottom of this page.

The page then goes on by showing the <a knowl="lmfdb/lfunction.euler_product">Euler product</a> formula of the
L-function. In the case of $\zeta(s)$, this was discovered by <a knowl="lmfdb/bio.euler">Euler</a>
and later used by Riemann as a starting point for the investigation of
prime numbers. In particular, Riemann showed that the distribution of
prime numbers is determined by the location of the zeros of
$\zeta(s)$.  All L-functions have an Euler product, i.e. they have an
expression as an infinite product over primes where the factor for
each prime is the inverse of a polynomial in $ p^{-s} $.

Next we find the imaginary parts of the first few zeros of the Riemann
zeta function.
Riemann's Hypothesis is that any non-trivial zero of the zeta function
has real part 1/2.  Moreover, it's hypothesized that any non-trivial
<a knowl="lmfdb/lfunction.zeros">zero</a> of any L-function has real part 1/2.  This has been verified for
every zero ever found. Consequently on these pages we only display the
imaginary parts of the zeros. The first non-trivial zero of the
Riemann zeta function
is at $ 1/2+ i 14.1347... $ and was actually computed by Riemann himself.
Now it is known that the first 10 trillion zeros of the Riemann zeta
function all have real part 1/2.
On these pages we have high precision rendering of the first 36
billion zeros; see [http://www.lmfdb.org/zeros/zeta/](http://www.lmfdb.org/zeros/zeta/).


Further information found on the Riemann zeta function page is the
list of values the function takes at some special points.  Again, this
is typical of L-functions. The <a knowl="lmfdb/lfunction.special_values">special values</a> of L-functions form a
remarkable area of modern research. The <a knowl="lmfdb/ec.q.bsdconjecture">Birch and Swinnerton-Dyer
Conjecture</a>, mentioned
above as one of the Clay Millennium problems, has to do with the
special values of L-functions
associated with <a knowl="lmfdb/ec.q">elliptic curves</a>.

Finally the page concludes by displaying the graph of the <a knowl="lmfdb/lfunction.zfunction">Hardy
Z-function</a>. This function has the same modulus as $\zeta(s)$ on the critical line, so its graph helps to provide a visual picture of the Riemann
zeta function. In particular, the Z-function has the same zeros as the
L-function and so for this one we can see the first zero at 14.1347...

In order to successfully navigate the L-functions pages you need to
know a little bit about how we classify L-functions. As we mentioned,
each L-function has a Dirichlet series, a functional equation, and an
Euler product.
We sort our L-functions first by <a knowl="lmfdb/lfunction.degree">degree</a>, then by <a knowl="lmfdb/lfunction.level">level</a>.

There is a certain amount of compatibility between these expressions.
For example, it is believed that the Euler product can always be
written as a product over  primes
of the inverse of a  polynomial in $p^{-s}$. In all known cases, at almost all
primes the
degree of this polynomial is the same as the number of
Gamma factors in the functional equation!

We specify a functional equation  by providing its <a knowl="lmfdb/lfunction.selbergdata">Selberg data</a>;
this is a 4-tuple which has the shape (
<a knowl="lmfdb/lfunction.degree">degree</a>, 
<a knowl="lmfdb/lfunction.level">level</a>, <a knowl="lmfdb/lfunction.spectral_parameters">Gamma-shifts</a>, 
<a knowl="lmfdb/lfunction.root_number">sign</a>),
or:

$ (d,N,(\mu_1,\dots , \mu_{J}:\nu_{1},\dots ,\nu_{K}),\varepsilon); $

Here the degree $d=J+2K$ is a positive integer, the level $N$ is a
positive integer, the $ \mu $ are complex numbers with non-negative real parts and
imaginary parts which sum to 0, and the sign $ \epsilon $ is a
complex number with absolute value $1$.  

For example, the LMFDB page for the Riemann zeta function indicates
the Selberg data are (1,1,(0:),1), where the first value 1 is the
<a knowl="lmfdb/lfunction.degree">degree</a>, the second is the <a knowl="lmfdb/lfunction.level">level</a>, (0:) indicates the <a knowl="lmfdb/lfunction.spectral_parameters">spectral
parameters</a> and the last 1 is the <a knowl="lmfdb/lfunction.sign">sign</a> of the functional equation.
