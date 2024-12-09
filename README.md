# larsen-c-bathymetry
Mapping the bathymetry underneath Larsen C Ice Shelf.
To do this, you will perform Sequential Gaussian Simulation (SGS) and Markov Chain Monte Carlo (MCMC) to perform gravity inversions.
Start by downloading all of the .py files, you will need these to run the code. Also download "larsen c full inversion.ipynb," as this includes instructions for running the inversion.
You will also need the conda package for python if you do not already have it downloaded.
The inversion begins with data processing, where the data is coarsened and variables are added. I have left the code there for reference and you will still need the code to add the 'res' variable to the BedMachine dataset, but the rest of this code can be skipped as I have uploaded the processed data under "Processed BM Data.nc" and "Processed Gravity Data.csv." You can start at the section titled "Make a target terrain effect using SGS and filter."
