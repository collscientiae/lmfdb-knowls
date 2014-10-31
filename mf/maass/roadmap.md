title: Roadmap for Maass forms
authors:
    fredstro
    john.jones
    DavidFarmer

Maass forms
==================


Navigation pages
------------------

- Make browsing more intuitive (how do people actually want to browse / search Maass forms?)
- Is it possible to keep information about where in the browse list we are, when going to the page for a specific Maass form?
- Maass forms arising from quadratic fields.
 
Home pages
------------------

- Add download of Fourier coefficients
- Make it possible to manipulate Fourier coefficients (i.e. test Hecke relations etc.)
- Get statics for Fourier coefficients, for example plots of value distribution (to see Sato-Tate) etc.
- Add plots of the Maass form in the fundamental domain.
- Add next / previous buttons (like on the Dirichlet character pages).

Available Data
------------------
- All Maass form data (for GL(2)/Q) is currently recomputed using sage/psage/cython.
 These computations should continue until we have data for all levels, at least up to 100. 
- Compute large sets of coefficients for all Maass forms in the database. 

Technical Issues
------------------

- The option to show "all" records does not work on the browse page.
- Fix the search so that it is also done with server-side dataTables so we can remove the 
  limit of 200 records (currently the client crash if we return more records)
- Try to make "tabbed" dataTables to make it possible to flip between different levels when browsing. 
 

Possible new subcategories
------------------
- Maass forms on the Picard group (these already exist in the database, but the corresponding pages needs to be revised).
- Harmonic weak Maass forms.
- Maass forms of half-integral weight.
