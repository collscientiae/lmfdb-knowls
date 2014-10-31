title: Roadmap for elliptic curves
authors:
    cremona
    DavidFarmer
    john.jones

Elliptic Curves
===============

Navigation pages
----------------

- Currently the search possibilities are rather limited, but if more search fields are introduced the search page will become very cluttered.  At that point we should only have very common options on the main page, with a separate "advanced search" page.  Examples include searching by [a1,a2,a3,a4,a6] or by [A,B].

Additional pages
----------------

- Add more to the Statistics page: currently this gives distributions of ranks, Shas and other things.
       
Additional data
---------------
- Currently the database contains all 2066197 elliptic curves defined over $\mathbb{Q}$ of conductor at most 330000.  
In future it is planned to add the much larger Stein-Watkins database, which includes curves with larger conductor.  This would not be complete.  Currently we do not have as much data about all the Stein-Watkins curves as for those in the Cremona database: for example we do not have generators for all the curve of rank 1.

- More data about each curve:  
 
  - Fisher has explicit models of genus one curves representing every element of [order 3](https://www.dpmms.cam.ac.uk/~taf1000/g1data/order3.html) and [order 5](https://www.dpmms.cam.ac.uk/~taf1000/g1data/order5.html) in Sha, and one could easily do similar for elements of order 2.  These could be shown on a curve's home page.

 - Automatic construction of quadratic twists of each curve from its home page; if the twist is not in the database we can still create a home page for it, with limited data.

Elliptic curves over number fields
----------------------------------

- Work has started to include elliptic curves over many number fields (real and imaginary quadratic and more).

- These will be linked to the associated modular forms where possible: Hilbert and Bianchi modular forms, etc.

- Automatic base change from the home page of every elliptic curve over $\Q$ to a number field, specified by its label.  Whether or not the resulting curve is in the database, its home page can be displayed.
