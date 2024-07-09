# NeuroSpec
![Neurospec](https://github.com/dmhalliday/NeuroSpec/assets/54075134/4a5511d9-b482-490c-b237-172fb8d3aacb)

## Background
**NeuroSpec** consists of a number of MATLAB functions for performing multivariate Fourier analysis of time series and/or point process (spike train or event) data, and plotting the results. The framework was designed primarily for use on neural data, but is suited to a wide range of stationary stochastic (random) signals. The following are available as ZIP files (MATLAB code) and PDF files (User guide):
1. NeuroSpec 2.0 & 2.01.  Bivariate spectral analysis, including routines for two channel auto spectral and cross spectral (coherence, phase, cumulant density) analysis, and a number of extensions including comparison of spectra, a stationarity test for spectra, comparison of coherence, system identification (gain, phase and impulse response), and pooled analysis (pooled spectra, pooled coherence, pooled phase, pooled cumulant density). Pooled analysis incorporates extended difference of spectra and extended difference of coherence tests.
2. NeuroSpec 2.11. Extensions for non-parametric directionality analysis of time series and spike train data. Includes unconditional directionality analysis for two signals and conditional directionality analysis for three signals.
3. Neurospec 2.2. Extension for optimal spectral tracking using adaptive Kalman filtering to track coherence over segments.


### References
Theoretical and practical aspects of the analysis are described in the following articles:
- Rosenberg, J.R., Amjad, A.M., Breeze, P., Brillinger, D.R. & Halliday, D.M. "The fourier approach to the identification of functional coupling between neuronal spike trains", Progress in Biophysics and molecular Biology, 53, 1-31, 1989. DOI: [10.1016/0079-6107(89)90004-7](http://dx.doi.org/10.1016/0079-6107(89)90004-7)
- Halliday D.M., Rosenberg J.R., Amjad A.M., Breeze P., Conway B.A. & Farmer S.F. "A framework for the analysis of mixed time series/point process data - Theory and application to the study of physiological tremor, single motor unit discharges and electromyograms", Progress in Biophysics and molecular Biology, 64, 237-278, 1995. [DOI: 10.1016/S0079-6107(96)00009-0](http://dx.doi.org/10.1016/S0079-6107(96)00009-0)
- Halliday D.M. "Nonparametric directionality measures for time series and point process data", Journal of Integrative Neuroscience, 14(2), 253-277, 2015. DOI: [10.1142/S0219635215300127](http://dx.doi.org/10.1142/S0219635215300127), Download: [Link](https://eprints.whiterose.ac.uk/120301/)
- Halliday D.M., Senik M.H., Stevenson C.W., Mason R. "Non-parametric directionality analysis – Extension for removal of a single common predictor and application to time series", Journal of Neuroscience Methods, 268, 87–97, 2016. DOI: [10.1016/j.jneumeth.2016.05.008](http://dx.doi.org/10.1016/j.jneumeth.2016.05.008)
- Halliday D.M., Brittain J-S., Stevenson C.W., Mason R. "Adaptive spectral tracking for coherence estimation: the z -tracker", Journal of Neural Engineering, 15(2), 26004, 2018. DOI:[10.1088/1741-2552/aaa3b4](http://doi.org/10.1088/1741-2552/aaa3b4)

## Acknowledgements
**NeuroSpec** code written by David Halliday. The following people have all contributed to the development of the framework: Jay Rosenberg, Bernie Conway, Abdul Majeed Amjad, Alex Rigas, David Murray-Smith, Joe Lau, Peter Breeze, Simon Farmer, Jens Nielsen, Yang Zhan, John-Stuart Brittain, Carl Stevenson, Rob Mason.

Development of NeuroSpec was supported in part by grants from the UK Joint Research Council Cognitive Science/HCI Initiative, The Wellcome Trust (Grants 036928; 048128; 058615), the UK Engineering and Physical Sciences Research Council (GR/R12350/01), and the UK Biotechnology and Biological Sciences Research Council (10477).

## History
**NeuroSpec** was previously hosted at [https://www.neurospec.org/](https://github.com/dmhalliday/NeuroSpec)
- NeuroSpec 1.0 Released Nov 2002.
- NeuroSpec 2.0 Released Feb 2008. Update to plotting (ver 2.01) released Jul 2016.
- NeuroSpec 2.1 Released Jun 2015.
- NeuroSpec 2.11 Released Jul 2016.
- NeuroSpec 2.2 Released Oct 2018.
### Contact
david.halliday@york.ac.uk

