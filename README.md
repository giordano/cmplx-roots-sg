General Complex Polynomial Root Solver and Its Further Optimization for Binary Microlenses
==========================================================================================

Paper
-----

J. Skowron & A. Gould (2012)

Full text: [ADS link](http://adsabs.harvard.edu/abs/2012arXiv1203.1034S) |
[arxiv.org link](http://arxiv.org/abs/1203.1034)

Abstract
--------

We present a new algorithm to solve polynomial equations, and publish its code,
which is 1.6-3 times faster than the `ZROOTS` subroutine that is commercially
available from *Numerical Recipes*, depending on application.  The largest
improvement, when compared to naive solvers, comes from a fail-safe procedure
that permits us to skip the majority of the calculations in the great majority
of cases, without risking catastrophic failure in the few cases that these are
actually required.  Second, we identify a discriminant that enables a rational
choice between Laguerre's Method and Newton's Method (or a new intermediate
method) on a case-by-case basis.  We briefly review the history of root solving
and demonstrate that "Newton's Method" was discovered neither by Newton (1671)
nor by Raphson (1690), but only by Simpson (1740).  Some of the arguments
leading to this conclusion were first given by the British historian of science
Nick Kollerstrom in 1992, but these do not appear to have penetrated the
astronomical community.  Finally, we argue that *Numerical Recipes* should
voluntarily surrender its copyright protection for non-profit applications,
despite the fact that, in this particular case, such protection was the major
stimulant for developing our improved algorithm.

Souce code
----------

Click here to download the whole package:
[cmplx_roots_sg.tar.gz](https://github.com/giordano/cmplx-roots-sg/archive/master.tar.gz).

Both code versions serve the same purpose, with the major difference being a
programing language.  Short reference of the subroutines is given at the
begining of the files and in the Appendix C of the Paper.  Purpose of each
subprogram and all its arguments are described at the begining of every
subroutine.  General ideas, limitations and comments are provided in the Paper.

The authors release the source codes associated with the Paper under terms of
the [GNU Lesser General Public License](http://www.gnu.org/licenses/lgpl.html)
version 2 or any later version, or under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0) as
well as under a "customary scientific license", which implies that if this code
was important in the scientific process or for the results of your scientific
work, we ask for the appropriate citation of the Paper
([Skowron & Gould 2012](http://arxiv.org/abs/1203.1034)).
