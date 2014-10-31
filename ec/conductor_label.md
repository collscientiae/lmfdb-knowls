title: Conductor labels for elliptic curves
authors:
    cremona

The LMFDB uses a systematic labelling of <a knowl="lmfdb/ec.conductor">conductors</a> of elliptic curves defined over each number field $K$.  The conductors are integral ideals of $K$.  Currently, two labelling systems are in use for an ideal $I$ of norm $N$:

- over imaginary quadratic fields $K$, the label of $I$ is $[N,c,d]$ where $d\mid N$ and the Hermite normal form $\mathbb{Z}$-basis of $I$ is $[a,c+d\alpha]$ where $a=N/d$ and the ring of integers of $K$ is $\mathbb{Z}[\alpha]$;
- over other fields, the label has the form $N.m$ where $m$ is the index (starting at $m=1$) of the ideal in a list of ideals of norm $N$.  The ordering of the ideals of fixed norm is recorded in the database.
