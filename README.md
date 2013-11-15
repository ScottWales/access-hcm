access-hcm
==========

ACCESS-HCM is a project from the ARC Centre of Excellence for Climate Systems Science to integrate a global quarter-degree ocean model into the Australian Community Climate and Earth-System Simulator (ACCESS) model.

Building the Model
------------------

Running the Model
-----------------

Technology Stack
----------------

Development:
 * Code Repository, Issue Tracking, Wiki - [Github](https://github.com/coecss/access-q)
 * Continuous Integration - ???

Model:
 * Ocean - [MOM](https://github.com/BreakawayLabs/mom) - [GPLv2](https://github.com/BreakawayLabs/mom/blob/master/LICENSE)
 * Sea Ice - [CICE](http://oceans11.lanl.gov/trac/CICE) - [Attribution](http://oceans11.lanl.gov/trac/CICE/wiki/CopyRight)
 * Atmosphere - UM - [Proprietary Licence](http://www.metoffice.gov.uk/research/collaboration/um-collaboration)
 * Coupling - [Oasis-MCT](https://enes.org/oasis/) - [LGPL](https://enes.org/oasis/download/oasis3-mct-copyright)

Interface:
 * Config tool - [Rose](https://github.com/metomi/rose/)?
 * Experiment Database - ???
 * Runtime dependencies - [Cylc](https://github.com/cylc/cylc)?
 * Data Publication - [Ramadda](http://ramadda.org)?
