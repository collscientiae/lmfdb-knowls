title: How to cite LMFDB
authors:
    gauss
    DavidFarmer

If you would like to acknowledge the LMFDB, please use a citation in the following form, alphabetized under _LMFDB_.

[42] The LMFDB Collaboration, _The L-functions and Modular Forms Database,_ 
[<code>http://www.lmfdb.org</code>](http://www.lmfdb.org), 2013, [Online; accessed 16 September 2013].

The BibTeX entry is:

 <pre><code>@misc{lmfdb,
  shorthand    = {LMFDB},
  author       = {The {LMFDB Collaboration}},
  title        =  {The L-functions and Modular Forms Database},
  howpublished = {\url{http://www.lmfdb.org}},
  year         = {2013},
  note         = {[Online; accessed 16 September 2013]},
}</code></pre>

Then you can cite a certain object much like quoting a specific theorem from a paper. For example, you may refer to the elliptic curve with LMFDB label 11a.2 by

<code>\cite[\href{http://www.lmfdb.org/EllipticCurve/Q/11.a2}{Elliptic Curve 11.a2}]{lmfdb}</code>

In order to make the <code>\url</code> and <code>\href</code> commands to work, one should use the [hyperref](http://ctan.org/pkg/hyperref) package.

----------------

To cite a specific page in the LMFDB, such as the home page of the L-function of the first
rank 4 elliptic curve/$\Q$ shown in the example below, you can cite it as

[42] The LMFDB Collaboration, _The L-functions and Modular Forms Database,_ 
Home page of the L-function $L(s,E)$ for the Elliptic Curve Isogeny Class 234446.a,
[http://www.lmfdb.org/L/EllipticCurve/Q/234446.a/](http://www.lmfdb.org/L/EllipticCurve/Q/234446.a/), 2013 , [Online; accessed 16 September 2013].

The BibTeX entry is:

 <pre><code>@misc{lmfdb:234446.a,
  shorthand    = {LMFDB E234446.a},
  author       = {The {LMFDB Collaboration}},
  title        =  { {\itshape {The L-functions and Modular Forms Database, 
      {\em Home page of the L-function $L(s,E)$ for the Elliptic Curve Isogeny Class 234446.a}}}},
  howpublished = {\mbox{\url{http://www.lmfdb.org/L/EllipticCurve/Q/234446.a/}}},
  year         = {2013},
  note         = {[Online; accessed 16 September 2013]},
}</code></pre>




