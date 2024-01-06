# polBpy
Dispersion Analysis of Dust-Polarimetric Data and Magnetic Field (**B**) strength.

## Description
***polBpy*** is an open-source library for the analysis of dust polarimetric data (Stokes *I, Q, U* maps; polarization angle $\phi$ and fraction *p*) with the purpose of studying the magneto-turbulent state of the gas.
The developement of this library was supported by the NASA/SOFIA Archival Research Program (Grant # USRA for Villanova University).

## Features
This library includes routines for peforming/calculating/studying:
1. The polarization-angle dispersion:
  - Calculate the two-point dispersion function (Houde+09).
  - Local dispersion (S; TBD).
  - MCMC fitting and parameter determination.
2. The plane-of-sky (POS) **B**-field strength using multiple David-Chandrasekhar-Fermi (DCF) approximations:
 - Classical;
 - Compressional;
 - Shear flow;

Also inlcude routines to implement the dispersion analysis over regions and create maps of **B** values.

## Installation
(TBF)
### Required packages
- Numpy
- Scipy
- Astropy
- Matplotlib
- emcee
- 

## Tutorials
A series of Jupyter notebooks can be found here. They show examples of basic and advanced usage of this library.

## References
### DCF Method
1. Classical DCF:

Davis51
```
Davis, L.,
“The Strength of Interstellar Magnetic Fields”,
Physical Review, vol. 81, no. 5, pp. 890–891, 1951.
```
[doi:10.1103/PhysRev.81.890.2.](https://doi.org/10.1103/PhysRev.81.890.2)

Chandrasekhar-Fermin53
```
Chandrasekhar, S. and Fermi, E.,
“Magnetic Fields in Spiral Arms.”,
The Astrophysical Journal, vol. 118, p. 113, 1953. 
```
[doi:10.1086/145731.](https://doi.org/10.1086/145731)

2. Compressional:

Skadilis+21
```
Skalidis, R. and Tassis, K.,
“High-accuracy estimation of magnetic field strength in the interstellar medium from dust polarization”,
Astronomy and Astrophysics, vol. 647, 2021.
```
[doi:10.1051/0004-6361/202039779](https://doi.org/10.1051/0004-6361/202039779)

3. Large-scale (Shear) Flow:

Lopez-Rodriguez+21
```
Lopez-Rodriguez, E., Guerra, J. A., Asgari-Targhi, M., and Schmelz, J. T.,
“The Strength and Structure of the Magnetic Field in the Galactic Outflow of Messier 82”,
The Astrophysical Journal, vol. 914, no. 1, 2021.
```
[doi:10.3847/1538-4357/abf934](https://doi.org/10.3847/1538-4357/abf934)

Guerra+23
```
Guerra, J. A., Lopez-Rodriguez, E., Chuss, D. T., Butterfield, N. O., and Schmelz, J. T.,
“The Strength of the Sheared Magnetic Field in the Galactic's Circumnuclear Disk”,
The Astronomical Journal, vol. 166, no. 1, 2023.
```
[doi:10.3847/1538-3881/acdacd](https://doi.org/10.3847/1538-3881/acdacd)

### Dispersion Analysis

Hildebrant+09
```
Hildebrand, R. H., Kirby, L., Dotson, J. L., Houde, M., and Vaillancourt, J. E.,
“Dispersion of Magnetic Fields in Molecular Clouds. I”,
The Astrophysical Journal, vol. 696, no. 1, pp. 567–573, 2009.
```
[doi:10.1088/0004-637X/696/1/567](https://doi.org/10.1088/0004-637X/696/1/567)

Houde+09
```
Houde, M., Vaillancourt, J. E., Hildebrand, R. H., Chitsazzadeh, S., and Kirby, L.,
“Dispersion of Magnetic Fields in Molecular Clouds. II.”,
The Astrophysical Journal, vol. 706, no. 2, pp. 1504–1516, 2009.
```
[doi:10.1088/0004-637X/706/2/1504](https://doi.org/10.1088/0004-637X/706/2/1504)

### Implementations

Chuss+19
```
Chuss, D. T., Andersson, B. -G., Bally, J., ...
“HAWC+/SOFIA Multiwavelength Polarimetric Observations of OMC-1”,
The Astrophysical Journal, vol. 872, no. 2, 2019.
```
[doi:10.3847/1538-4357/aafd37](https://doi.org/10.3847/1538-4357/aafd37)

Guerra+21
```
Guerra, J. A., Chuss, D. T., Dowell, C. D., Houde, M., Michail, J. M., Siah, J., Wollack, E. J.,
“Maps of Magnetic Field Strength in the OMC-1 Using HAWC+ FIR Polarimetric Data”,
The Astrophysical Journal, vol. 908, no. 1, 2021.
```
[doi:10.3847/1538-4357/abd6f0](https://doi.org/10.3847/1538-4357/abd6f0)

## Licensing

## Other Links