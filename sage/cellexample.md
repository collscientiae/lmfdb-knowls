title: Sage cell example
authors:
    gauss

Here is an example of a Sage cell. (Embedded magic provided by the <a href="http://sagecell.sagemath.org/">Sage cell server.</a>)

<script src="http://sagecell.sagemath.org/static/jquery.min.js"></script>
<script src="http://sagecell.sagemath.org/static/embedded_sagecell.js"></script>
<script>sagecell.makeSagecell({"inputLocation": ".sage"});</script>

<style type="text/css">
.sage .CodeMirror {
  height: auto;
}
</style>

<div class="sage">
  <script type="text/x-sage">
F = GF(31)                       
P.<x> = PolynomialRing(F)        
H = HyperellipticCurve(x^5+2*x+1)
H.frobenius_polynomial()         
</script>
</div>
