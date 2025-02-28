What Is New in *genieclust*
===========================

genieclust 1.0.0 (2021-04-22)
-----------------------------

-  [R] Use ``mlpack`` instead of ``RcppMLPACK`` (#72). This package is
   merely suggested, not dependent upon.

genieclust 0.9.8 (2021-01-08)
-----------------------------

-  [Python] Require Python >= 3.7 (implied by ``numpy``).

-  [Python] Require ``nmslib``.

-  [R] Use ``RcppMLPACK`` directly; remove dependency on ``emstreeR``.

-  [R] Use ``tinytest`` for unit testing instead of ``testthat``.

genieclust 0.9.4 (2020-07-31)
-----------------------------

-  [Bugfix] [R] Fix build errors on Solaris.

genieclust 0.9.3 (2020-07-25)
-----------------------------

-  [Bugfix] [Python] Add code coverage CI. Fix some minor
   inconsistencies. Automate the ``bdist`` build chain.

-  [R] Update DESCRIPTION to meet the CRAN policies.

genieclust 0.9.2 (2020-07-22)
-----------------------------

-  [BUGFIX] [Python] Fix broken build script for OS X with no OpenMP.

genieclust 0.9.1 (2020-07-18)
-----------------------------

-  [General] The package has been completely rewritten. The core
   functionality is now implemented in C++ (with OpenMP).

-  [General] Clustering with respect to HDBSCAN*-like mutual
   reachability distances is supported.

-  [General] The parallelised Jarnik-Prim algorithm now supports
   on-the-fly distance computations. Euclidean minimum spanning tree can
   be determined with ``mlpack``, which is much faster in
   low-dimensional spaces.

-  [R] R version is now available.

-  [Python] [Experimental] The GIc algorithm proposed by Anna Cena in
   her 2018 PhD thesis is added.

-  [Python] Approximate version based on nearest neighbour graphs
   produced by ``nmslib`` is added.

genieclust 0.1a2 (2018-05-23)
-----------------------------

-  [Python] Initial PyPI release.
