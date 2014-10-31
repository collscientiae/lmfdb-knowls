title: Discriminant exponent of a local field
authors:
    john.jones
    gauss

The **discriminant** of a <a knowl="lmfdb/lf">local field</a> $K$ is the square of the determinant of the matrix
\[
\left( \begin{array}{ccc}
 \sigma_1(\beta_1) & \cdots & \sigma_1(\beta_n) \\
\vdots & & \vdots \\
\sigma_n(\beta_1) & \cdots & \sigma_n(\beta_n) \\
\end{array} \right)
\]
where $\sigma_1,..., \sigma_n$ are the embeddings of $K$ into an algebraic closure $\overline{\mathbb{Q}}_p$, and $\{\beta_1, \ldots, \beta_n\}$ is an <a knowl="lmfdb/lf.integral_basis">integral basis</a> for the ring of integers of $K$.  

The discriminant of $K$ is an element of $\mathbb{Z}_p$ which is well-defined up to the square of a unit.  Thus, it is of the form $p^c u$ where $u$ is a unit.  The value $c$ is the discriminant exponent for $K$.  Together with the <a knowl="lmfdb/lf.discriminant_root_field">discriminant root field</a> of $K$, it determines the discriminant of $K$ (up to the square of a unit).
