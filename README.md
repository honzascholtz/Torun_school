# What do after running through the Jupyter notebooks: 

After we have finished with the Jupyter Notebooks and we have the code to analyze our IFU observations, we can now go and focus on the science we can do with the data. You can choose of two projects:

## A) ISM and dust properties. 
In this part of the project we will instead focus on the ISM properties of our source. 

1. Fit the individual blobs in the system to get Halpha, [NII], [OIII] doublet, Hbeta, [SII] double.
2. Use Halpha/Hbeta to estimate Av and correct your emission lines for dust extinction
3. Estimate Metallicity of blobs using N2 and R3 ratios from Curti+2020
4. Use corrected Halpha lum to estimate the SFR of your system
5. Do the same on spaxel by spaxel to map the Av, SFR, ISM, and SFR surface density (SFR/unit of area of spaxel) 

z = 3.471
Scale of 0.14 kpc^2 / spaxel - now we can scale down SFR to SFRD

6. Plot maps of SFR surface density with Av contours to see any correlation between SFR density and dust extinction
7. Using the stellar mass from Isabella’s paper you can place these objects on mass-metallicity plane - compare it to those from Mirko Curti 2024 MZR relation (OR: done spaxel-spaxel fitting, will put the apertures in the next session)
8. Estimate the density from [OII] and [SII] using Sanders et al. (2016)  - can you map the densities of just integrated z? (OR: done for spaxel-by-spaxel)


## B) Kinematics and outflows of this merger
In this part of the project, you main aim is to analyze the kinematics of the merger and also analyze the outflow properties of this system. You can:

1. Extract spectra of the different blobs and put them on the BPT diagram to determine if any blob hosts an AGN (OR: almost done)
2. Fit the cube with two models to decompose the narrow and broad components on the [OIII] and Halpha emission lines (OR: almost done)
3. Create a map of the broad component only and extract the aperture from that region 
4. From the integrated spectrum of the outflow region:
  a) Estimate density of gas using the [SII] doublet - Sanders 2016
  b) Estimate the outflow velocity - outflow_vel + FWHM
  c) Estimate the mass of the outflow - Use relation from Carniani+2015
  d) Size of the outflow - map the outflow and see how many pixels it is across
  e) Mass outflow rate  - Use Carniani+2015 
  f) Plot the emission line ratio of the outflow on the BPT diagram - what is driving it? SF or galaxies?
  g) Estimate SFR from Halpha and estimate mass loading factor - Mass outflow rate/SFR - what is the dominant source of gas consumption 


