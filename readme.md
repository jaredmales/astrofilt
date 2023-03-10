Astrofilt is a collection of astronomical filter curves by Jared Males.

FORMAT:

The ASCII data files, with extension .dat, are in 2 column format with:

 wavelength  transmission

Wavelength is specified in microns

Transmission is between 0 and 1 (inclusive), and all curves are here normalized so that the maximum is 1.0

Comment lines begin with #.

NAMING:

Filter names are standarized as 'X_System' where X indicates the bandpass, and System is the instrument or photometric system.

DATA SOURCES:

The data are collected from various sources, and the comments at the beginning of each .dat file indicate history.  Where
necessary the data has been processed to convert wavelength to microns and normalize transmission.  The curves are
frequently digitizations of plots, and the source of the plots is indicated.  The 'raw' directory contains some of the
original files and working images used for the various processing steps.

ATMOSPHERE:

We have collected 0 airmass curves whenever we can tell the difference.  Detector QE, mirror reflectance, etc., are
included where appropriate.  In other words it's up to you to deal with the atmosphere.

SOURCE CODE:

Source files for idl and matlab are provided.  Both assume that you have defined ASTROFILT_DATADIR in your environment path.  
See the files for further help and understanding.  C code will be added soon.


