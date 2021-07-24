---
title: "FELIS"
excerpt: "Finding Emission Lines In Spectra uses template matching to search for features in 1D spectra"
collection: software
date: 2021-07-24
---
FELIS is a simple Python tool that can be used to match a given set of emission line and/or spectral feature templates to 1D spectra. The software is preseneted by Schmidt et. al (2021, accepted by A&A). FELIS includes routines to generate templates on the right format, and then uses the standard chi2 minimization to match the template, and estimate the significance of the match (S/N). FELIS was buld to work with 1D spectra on the [TDOSE](<https://github.com/kasperschmidt/TDOSE>) format, but also provides a function to generate such spectra, from any 1D septrum. Further details can be found in the Appendix by Schmidt et al. (in prep.) and in the readme file available together with the code at 

<https://github.com/kasperschmidt/FELIS>

<center>
<img src='/images/FELISlogo.png' width='600'>
</center>
