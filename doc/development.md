title: Developers Guide
authors:
    DavidFarmer

LMFDB Developers Guide
=======================

This document describes the principles behind
the pages in the LMFDB, the writing style, the use of knowls,
and the URLs of the home paes of mathematical objects.
This document is not meant as a rigid set of rules.
Rather, it is intended to help speed the creation and
adoption of new material, and to help maintain a unified
design as the website grows.

Adding material to the LMFDB
----------------------------

Two main principles guide the development of pages.

1) New pages are developed at a workshop, through an
iterative process that involves input from both experts
and nonexperts.  The goal is to make everyone happy.

2) The closer a page is to the top, the more scrutiny
by more people is required.

A corollary of the last sentence in 1) is that a novice
must be able to click their way around the site, exploring
objects about which they know very little, and an expert has
to be able to quickly find what they are looking for.
Hence the need for 2), because only a large and diverse
group will represent all the perspectives, hence the need
for the first phrase in 1).

The pages in the LMBDB
======================

* Each mathematical object in the LMFDB has a "home page."

* The home pages can be reached by browse-and-search pages.

* On the home page and the browse-and-search page, knowls
  provide information about technical terms.

* Each home page lives at a mathematically meaningful URL.

We elaborate on those four points.

Homepages
---------

Every object in the LMFDB has a "home page."  The home page of
a mathematical object is based on the idea of the home page of
a mathematician, or the wikipedia article of someone famous.


An object's home page should provide a wide variety of
information about the object.  Basic information, of interest to
both experts and non-experts, should appear near the top.  More
specialized information should appear near the bottom.

In the upper right corner of the home page should be the "properties"
box, summarizing the most basic facts about the
object.  The information in the properties box should also appear
in the body of the page.

Below the Properties box is the Related objects box, containing
links to the home pages of related objects.  And below the
Related objects box is the Downloads box, containing links
to data.

Standard practice for creating the home page for a new object is to
copy the template for an existing object with a good home page
(elliptic curves or global number fields have been common choices)
and then modify it.  The Properties box and other features will
already be there, and you can use them without necessarily knowing
all the details of how the templates work.

*Historical note:* the Properties box is also known as the "Lady Gaga"
box.  The name comes from from John Voight's presentation at an LMFDB
workshop of Lady Gaga's Wikipedia article, illustrating the value of
gathering basic information in the upper-right corner of a home page.

*Use knowls:* Descriptions of the terminology on a home page should
be put in knowls.  This allows nonexperts to find basic
information, without forcing experts to skim through all the
documentation.  The links to the knowls should be the words
being defined.  Don't add extraneous words like "click here".

*Get feedback* from both experts and nonexperts about the order in which
the information appears on the home page, and the categories in which to
group the material.  If there is a question about whether something
should go on a home page, almost always the answer is 'yes,' and you
can always put it near the bottom.  The main exception is when the
information is not of wide interest, and it more properly belongs on
the home page of a related object.

Browse-and-search
-----------------

The entry point to a mathematical object in the LMFDB is by its
browse-and-search page.  The upper portion of that page,
that part that is visible in a typical browser when you click
to the page, should contain two things:

1) At the top should be a variety of links to specific objects,
and to search pages where reasonable search parameters have already
been selected.  The point is that a novice should be able to
click around with their mouse and explore the topic, without
needing to fill out a form or even know anything about the topic.

2) Below the browsing section, but still visible without scrolling,
should be a search form which is suitable for use by experts.

Other material can appear in the lower portion of the browse-and-search
page.

Knowls
======

Anatomy of a knowl
------------------

There are three components to a knowl:

1) Identifier.  This indicates where the knowl fits into the hierarchy
of information in the LMFDB, but the scheme is not as elaborate or
as rigid as the URLs.

Example: ec.q.conductor

Consult with experts before introducing new first- or second-level
identifiers, because it is quite tedious to alter identifiers and
change all the places they are used.

2) Description (Some people think of this as the "Title" of the knowl, but titles tend to be shorter than descriptions.) This is several words that describes the knowl and helps distinguish it among knowls on similar topics.

Example: Conductor of an elliptic curve over $\Q$

(That description would be inadequate if it were any shorter.)

3) Content.  This is the text that appears when someone clicks on the knowl.

As originally envisioned by Harald Schilly, knowls should contain a
relatively small amount of information (because it is better to have
knowls-within-knowls so the reader can determine what additional
information is needed), and the content of a knowl should be
*context independent*.  This means that the information should make sense
wherever it might appear.

In the example of "Conductor of an elliptic curve over $\Q$," the definitions
in most textbooks may not be suitable for the content of the knowl, because
the phrasing may not make sense unless the reader has just read the previous
paragraphs.

Years of schooling have trained people to write in a linear fashion
where each idea flows into the next.  This training actually makes it
difficult to write knowls.  Try not to think about the specific situation
in which you want to use the knowl: write something that makes sense in
all the other places where other people might use it.

Using knowls
------------

Knowls are used in several ways:

1) To provide supplementary information (such as a definition)
on a web page.

2) To provide all of the material on a web page, in a way that
can easily be edited.  (This is the "knowl include" option.)

3) To give details about the material only on one specific web page
or a specialized set of web pages.

The above is a list of how knowls *are* currently used in the LMFDB.
It has been suggested that the 3rd item is not the proper use of a knowl,
and that there are better ways to achieve the same results.

(( more discussion is needed here ))

URLs
====

One of the fundamental principles of the LMFDB is that
mathematical objects should have a "home page," where we follow
the analogy of the home page of a person as much as possible.
Below we describe the scheme for URLs of home pages.


As much as possible, the URLs for the home pages of objects
in the LMFDB should be:

1. mathematically meaningful
2. human readable
3. permanent
4. suitable for inclusion in a bibliography

Here and throughout this document, we say "should" instead of "must,"
with the understanding that some compromises will be inevitable.

Note that "unique" is not on the list of desirable properties of a URL.
Multiple URLs are inevitable because part of the beauty of the subject
is that the same object can arise in several ways.

Some principles:

**1)** If X is the URL of an object, then L/X is the  URL of its standard
L-function.  According to the Langlands program, other L-functions
associated to X have the form L(s,X,rho).  Examples are

L(s,f,\sym^2)

L(s,Upsilon,\spin).

Those have URLs, respectively,

L/SymmetricPower/2/urlforf

L/spin/urlforUpsilon

**2)** The group comes before the field

For example, GL2/Q could occur in the URL of some object.

**3)** The "type of object" should come first.  The following is the current
list of top level URLs for home pages of objects.  Note: there are
other top level URLs, but these are all that currently have home pages
of objects below them.

* /ArtinRepresentation
* /Character
* /EllipticCurve
* /GaloisGroup
* /L
* /LocalNumberField
* /ModularForm/
* /Motive
* /NumberField

**4)** "Nicknames" can be used for popular number fields.

The current list of number field nicknames is:

QsqrtN  :  where "N" can be a positive or negative integer. For
example: Qsqrt7 or Qsqrt-5

Q   : the rationals $\Q$

Qi  : $\Q(\sqrt{-1})$

QzetaN  :  the Nth cyclotomic field

For example, Hilbert modular forms on $\GL(2)/\Q(\sqrt{5})$ could go
under   /ModularForm/GL2/Qsqrt5

Note that number field $\Q(\sqrt{5})$ has an "official" name as
well as a nickname, so the above is not the only initial segment
of a URL for those Hilbert modular forms.  See the below for a
a discussion of number field labels.

**5)**  The URL of an object provides successively narrower descriptions
of the object.  After some number of levels (depending on the object)
one is faced with the issue of naming a specific object.  This
final specification can be done with a label consisting of an
alphanumeric string, or it can be done with a hierarchy/directory-style
specification of alphanumeric strings separated by slashes (/).
The specific approach should be appropriate to the object under
consideration.

The following examples are currently in use, and these URLs probably
should be considered "permanent", except possibly for the \<label\>s:

* /ArtinRepresentation/\<dim\>/\<conductor\>/\<label\>
* /Character/Dirichlet/\<modulus\>/\<number\>
* /Character/Hecke/\<number_field\>/\<modulus\>/\<number\>
* /EllipticCurve/Q/\<label\>
* /GaloisGroup/\<label\>
* /LocalNumberField/\<label\>
* /ModularForm/GL2/Q/holomorphic/\<label\>
* /ModularForm/GL2/Q/Maass/\<label\>
* /Motive/Hypergeometric/Q/\<label\>
* /NumberField/\<label\>

The following URL is in use but is not consistent with the above
principle (at minimum, GSp should probably be GSp4 for genus 2 examples):

/ModularForm/GSp/Q/\<label\>


Some Labeling issues
--------------------

Discussion is needed about \<label\>s.  In particular:

a) The possibility, and desirability, of consistent labels for different
types of modular forms: Holomorphic, Hilbert, Bianchi, Siegel.

b) Possible new labels for number fields, if the current scheme is not
suitable for Artin representations or Hecke characters. (See Issues 128 and
127 in the issue tracker.)

c) If an object naturally belongs to a Galois orbit, then the members of
that orbit are given a unique (but possible arbitrary) name.  The
name of the Galois orbit (which typically is a letter or a string of
letter if there are more than 26 Galois conjugates) is the final
component of the label of the object.
