Reference  The precise CCD positions of Phoebe using Gaia DR3 catalogue  
           (Wang+ 2025)
===============================================================================
Complementary positions of Yunnan Observatory 2.4m and 1.0m telescope of Phoebe
N. Wang, Z. Y. Xue, B. B. Zhang, Q. Y. Peng, X. M. Cheng, Y. M. Ye
   <Reference (2025)>  = 2025jjjjjvvvvLppppA
===============================================================================
ADC_Keywords:  Solar system; Planets; Positional data
Keywords: image processing, astrometry,planets and satellites: individual: Saturn 

Abstract: 
    Phoebe was observed in 2023 and 2024 by Yunnan Observatory 1.0m telescope.
    These observations, along with those obtained from 2011-2014 by Yunnan
    Observatory 2.4m telescope, were processed using the Gaia DR3 star catalogue.
    To improve positional measurements, the two-dimensional Gauss fit or the
    effective point spread function was applied. During the reduction, the
    geometric distortion of the calibration field was solved, the precision 
    premium was reduced, and the differential color refraction was accounted for.
    A total of 368 CCD observations were obtained. The theoretical position of 
    Phoebe was derived from IMCCE ephemeris ph12 and Saturn’s position from JPL
    ephemeris DE441. The results show that the mean (O-C) is -0.002 and 0.016 
    arcsec in right ascension and in declination, respectively. The dispersion
    of our observations is 0.028 and 0.028 arcsec in right ascension and in 
    declination, respectively.

	
Description: 
	This table contains 368 positions of the Saturnian satellites Phoebe 
	from Yunnan Observatory 2.4m and 1.0m telescope that were taken in 2011-2014
        and 2023-2024, respectively. The field of view for the 2.4m telescope is
        ~0.16{deg}, and its approximate scale factor is ~0.286 arcsec/pixel, for
        the 1.0m telescope is ~0.266{deg} or ~0.119{deg}, and its approximate 
        scale factor is ~0.234 arcsec/pixel or ~0.209 arcsec/pixel. Positions of
        Phoebe are provided in right ascension and declination. RA and DE are
        given in the observed topocentric apparent positions without atmospheric.
        refraction. JD is the Julian Date(UTC).


File Summary:
--------------------------------------------------------------------------------
 FileName   Lrecl  Records  Explanations
--------------------------------------------------------------------------------
ReadMe         80     .     This file
table.dat      53    368    positional measurement of Phoebe.

See also:
 J/A+A/391/767   : CCD observations of Phoebe in 1998-1999 (Fienga+, 2002)
 J/MNRAS/366/208 : Precise positions of Phoebe (Peng+, 2006)
 J/A+A/454/379   : 2003-2004 Phoebe CCD astrometry (Qiao+, 2006)
 J/MNRAS/413/1079 : 2005-2008 Phoebe CCD astrometry (Qiao+, 2011)
 J/MNRAS/449/2638 : 2011-2014 Phoebe CCD astrometry (Peng+, 2015)

Byte-by-byte Description of file: table.dat
--------------------------------------------------------------------------------
   Bytes Format Units          Label     Explanations
--------------------------------------------------------------------------------
   1- 03  A3     ---           IAU code  the IAU code for the telescope
   7- 20  F14.6  day           JD        the Julian Date of the observation
  24- 25  I2     h             Hour      Phoebe's right ascension
  27- 28  I2     m             Minute    Phoebe's right ascension
  31- 37  F7.4   s             Second    Phoebe's right ascension
  39- 41  I3     ◦            degree    Phoebe's declination
  43- 44  I2     '             arcmin    Phoebe's declination
  47- 52  F6.3   "             arcsec    Phoebe's declination

--------------------------------------------------------------------------------

Notes:
Note (N1): RA and DE are given in the observed topocentric apparent positions. 
--------------------------------------------------------------------------------

Acknowledgements:

   Na Wang,  twangna(at)jnu.edu.cn
================================================================================
(End)        Na Wang [JNU]        Dec-2025 