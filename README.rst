###########################################################################################
HeadingFromGPS: A MATLAB Tool to Calculate Heading and Distance between Two GPS Coordinates
###########################################################################################

*HeadingFromGPS* is a MATLAB-based software tool for the estimation of the heading/bearing and distance between two GPS coordinates, a *source* and *target*.  It's output is the provision of these results with robustly quantified uncertainties, obtained via a Monte Carlo method.  *HeadingFromGPS* uses Vincenty's formulae for the WGS-84 oblate spheroid Earth.

************
Installation
************

*HeadingFromGPS* is available as a source distribution and a build distribution and is hosted on `GitHub <https://github.com/bradleymconrad/HeadingFromGPS>`_.  If you have a MATLAB license (R2019a or newer), add the "source" directory to the MATLAB path and run "HeadingFromGPS". Alternatively, double-click the "HeadingFromGPS_Installer" executable in the "build" directory to install a standalone version of the software on your computer (requiring install of the MATLAB runtime).

To clone the *HeadingFromGPS* repository, see GitHub's `instructions <https://help.github.com/en/articles/cloning-a-repository>`_.

  Note: When booting the software, the landing screen may disappear and it may seem as though booting has stalled. Be patient at this point; background processes are running and *HeadingFromGPS* will initialize shortly after.

Requirements
============

*HeadingFromGPS* was developed and has been tested in MATLAB R2019a, and uses the *statistics_toolbox*.

If you encounter issues during installation or when using *HeadingFromGPS*, please contact the author.

**********
Contribute
**********

Consider contributing in the following ways:

  1. Have a bug report? Raise an issue on github.

  2. Want to introduce functionality helpful to your work/field? Fork the repository, make it work for you, and issue a pull request. Credit will always be given!

*******
License
*******

*HeadingFromGPS* is licensed under the **MIT** license:

**************************
Author Contact Information
**************************

You can contact Bradley (Brad) Conrad with issues and/or recommendations at brad.conrad@carleton.ca or brad.m.conrad@gmail.com

***************
Version History
***************

**Version 1.0**: Version/release at time of first posting to GitHub.

****************
Acknowledgements
****************

*HeadingFromGPS* was developed at Carleton University's `Energy and Emissions Research Laboratory <http://www.carleton.ca/eerl>`_ as part of the `Sky-LOSA Project <http://www.flarenet.ca/research/sky-losa-measurement-of-black-carbon-soot-emissions-from-gas-flaring>`_ with support from `NSERC FlareNet <http://www.flarenet.ca>`_.

.. image:: images/Logo_EERL.png
   :scale: 20 %
   :align: center
   :target: http://www.carleton.ca/eerl

|

.. image:: images/Logo_FlareNet.png
   :scale: 20 %
   :align: center
   :target: http://www.flarenet.ca
