# ghost_specutils
Tools for working with reduced GHOST spectra

## plotting_ghost_spectra.ipynb

Jupyter notebook for plotting GHOST spectra either order-by-order or the combined and interpolated spectra, and a script for plotting and saving a full GHOST spectrum to a single pdf

## combine_ghost_spec.ipynb

Jupyter notebook for reading in and combining multiple exposures of GHOST spectra and plotting the combined spectra or their S/N

## combine_ghost_spec_fix_clocking.ipynb

Jupyter notebook that expands on combine_ghost_spec.ipynb to read in multiple spectra and correct the wavelength solutions for an issue in the binned data that isn't properly treated in GHOSTDR yet

## specnormrv_example.ipynb

A Jupyter notebook that can be used to 1) calculate RVs from cross-correlation with a template spectrum (one metal-poor template is provided in this repo) and shift the input spectrum to an RV of 0, 2) calculate the barycentric RV correction and apply it to the measured RVs, 3) perform a fine normalization using the input template spectrum to identify continuum points in the input spectrum, and 4) combine the spectra from GHOST's red and blue cameras.
