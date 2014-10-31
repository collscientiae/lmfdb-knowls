title: Normalization of defining polynomials for number fields
authors:
    john.jones
    DavidFarmer

A number field can be <a knowl="lmfdb/nf.defining_polynomial">defined</a> by many different irreducible polynomials $f(x)\in\Q[x]$.
The normalized polynomial is the output of gp/pari's <code>polredabs</code>, which is effectively a canonically chosen defining polynomial.

Normalized polynomials are always monic with integer coefficients, such that the sum of the squares of the absolute values of all complex roots of $f(x)$ is minimized.  When there is more than one such polynomial, the tie is broken based on the size of the polynomial's coefficients and discriminant.
