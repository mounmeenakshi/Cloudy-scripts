The cloudy scripts are used to evaluate a radio loud AGN spectrum matched to Shang et. al (2011). 
We used the shang_incident_sed.in to propgate the incident spectrum through the Broad Line Regions (BLR), which saves the transmitted spectrum file (.txt) from the BLR.
The generated transmitted spectrum file is used in by the shang_final_sed.in. to obtain the final SED.
The incident SED has a total luminosity of 10^45 erg/s, and all the components can be easily scaled for differnet luminosities. 
We assume a covering factor of 30% for the BLR, and thus the final SED constitues 70% of the incident and 30% of the transmitted value.
