Overview of the pbbarcode package
=================================

The *pbbarcode* package provides tools for annotating PacBio
sequencing reads with barcode information. Typically, *pbbarcode*
is called in context of a SMRTPipe workflow as opposed to directly on
the command line, however, users are encouraged to utilize the
command-line utility directly, as more options are available.  

The *pbbarcode* package provides a multi-command line tool
*pbbarcode* which currently has the following sub-commands:  

* labelZmws
* labelAlignments
* emitFastqs
* consensus

The first three sub-commands depend on only *pbcore* and its
dependencies, the fourth, *consensus*, depends on the *pbdagcon*
package and is considered experimental.  

For more details on the package, please see docs/index.rst for more
information.

Installation
============

Typically, the *pbbarcode* package is installed within an installation
of SMRTPipe, however, it can be installed by itself using::

   make install

To test that everything is installed correctly, one should
additionally issue a::

   make test

DISCLAIMER
----------
THIS WEBSITE AND CONTENT AND ALL SITE-RELATED SERVICES, INCLUDING ANY DATA, ARE PROVIDED "AS IS," WITH ALL FAULTS, WITH NO REPRESENTATIONS OR WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTIES OF MERCHANTABILITY, SATISFACTORY QUALITY, NON-INFRINGEMENT OR FITNESS FOR A PARTICULAR PURPOSE. YOU ASSUME TOTAL RESPONSIBILITY AND RISK FOR YOUR USE OF THIS SITE, ALL SITE-RELATED SERVICES, AND ANY THIRD PARTY WEBSITES OR APPLICATIONS. NO ORAL OR WRITTEN INFORMATION OR ADVICE SHALL CREATE A WARRANTY OF ANY KIND. ANY REFERENCES TO SPECIFIC PRODUCTS OR SERVICES ON THE WEBSITES DO NOT CONSTITUTE OR IMPLY A RECOMMENDATION OR ENDORSEMENT BY PACIFIC BIOSCIENCES.
