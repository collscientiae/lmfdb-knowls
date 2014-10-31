title: Labels of elliptic curves over number fields
authors:
    cremona

The label of an elliptic curve over a number field $K$ has three components, denoting the conductor, the isogeny class and the isomorphism class:

- The <a knowl="lmfdb/ec.conductor_label">conductor label</a> depends on the field;
- The <a knowl="lmfdb/ec.isogeny_class">isogeny class</a> label consists of one or more letters a-z or A-Z; the ordering of the isogeny classes is based on lexicographical ordering of the Dirichlet coefficients of the L-series;
- The isomorphism class is a positive integer giving the index (starting at 1) of the curve in its <a knowl="lmfdb/ec.isogeny_class">isogeny class</a>.

Together these give a label of the form $N.a1$ where $N$ is the conductor label, $a$ the class and $1$ the curve number.

In addition, to specify the elliptic curve completely prepend the label of the base field to give a full label of the curve, for example 3.0.23.1-89.1-A1.
