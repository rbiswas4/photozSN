# SN light curve characterizaton without strong prior knowledge of redshift

This is a project to study characterization of SN light curves with partial
information on the redshift of the SN.

## Contents 
- docs/Outline.rst : 
- docs/Plans.rst : A rough plan of how I think the project will proceed
- docs/Fitting_Template.ipynb: A fitting tutorial that has been written to get one up to speed on using these.
- docs/Supernova_Ia.ipynb : an ipython notebook showing the impact of redshift on light curves
- graphics/2011-fe.mp4 : A animation showing the spectral evolution of 2011-fe from assorted data combined as a `~TimeSeries` object. Phase is the rest frame time in units of days measured from an "explosion date". $\lambda$ is the wavelength in Angstrom. The flux values are in `arbitrary units` rather than in physical units, but the relative normalization is taken into account. Note also that something is wrong about this as we are using estimates from dim data without errors, leading to negative values at some times.
