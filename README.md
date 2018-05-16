# Using sky coordinates
*Marco Gullieuszik*

`SkyCoord` is an `astropy` class providing a flexible interface for celestial coordinate representation, manipulation, and transformation between systems.

I will present a few scripts to show how to use `SkyCoord` objects to:
- convert and transform celestial coordinates: equatorial/galactic, decimal/hmsdms
- match astronomical catalogs
- transform from pixel to world coordinates (and viceversa) using the WCS of a FITS image
- make plots with sky coordinates