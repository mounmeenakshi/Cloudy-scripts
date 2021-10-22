The cloudy scripts were used to evaluate a realistic radio loud AGN spectrum, which is consistent with the mean SED from Shang et. al (2011).
First, we used the script shang_incident_sed.in to propgate the incident spectrum through the Broad Line Regions (BLR), which saved the transmitted spectrum file (.txt). The generated transmitted spectrum file is used by the shang_final_sed.in to produce the final SED (shown in the paper).
The incident SED has a total luminosity of 10^45 erg/s, and all the components can be easily scaled for differnet luminosities. 
We assume a covering factor of 30% for the BLR, and thus the final SED constitues 70% of the incident and 30% of the transmitted value.

The final SED was propagated through the ISM along each Line of Propagation (LOP), where we used ionisation fraction=0.5 as the stopping critera for the Raditive Transfer in our study. The RT run saves an overview file (.ovr) for each LOP, which contains the data on temperature, density, ionisation fraction, etc. as a function of depth.
