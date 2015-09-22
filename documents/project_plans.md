Project plans for the collaboration
===================================

Synopsis
--------

<a href='https://github.com/ARM-DOE/pyart'> Py-ART, The Python ARM Radar Toolkit
</a> was invented to help scientists interact with and visualize weather radar
data. One of the key capabilities we have been working on is the ability to
dealias radial velocities. This is especially important to DoE ARM as we work at 
X and C bands.

The Meteorological Service of Catalan has a network of radars (C-band, single-polarisation)
which use dual PRF to produce dealiased radial velocities (for use in forecast and ingestion?).
One issue that scientists are addressing is these pulse techniques can fail.

The key area of commonality is we are both interested in the data quality of
radial velocities and wish to build tools to asses this to allow us to focus on
times that need improving. 

Project Plans
-------------

###1) Develop an IPython Gallery of examples of failed dealiasing we wish to detect
Details

###2) In Py-ART develop code that metrics of "Quality" of the velocity
Details

###3) Develop a climatology in both ARM and Meteocat radar data
Details




