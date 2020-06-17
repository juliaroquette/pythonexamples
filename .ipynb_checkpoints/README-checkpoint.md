# pythonexamples
Jupyter-notebooks with useful python examples for quick reference

Created this repository to put together a series of examples of python I have collected/built.

## `MultiplePlots` include:

  Figures with multiple plots using:
  - `plt.subplots`
  - `plt.subplot2grid`
  - `GridSpec`
  Including:
  - grids of equal size
  - grids of different sizes
  - grids inside `for`

  Some plot adjust:

  - remove tick labels
  - change space between plots
  - share axis
  - axis scale
  - various tick label adjustments

  A more complex example:

  - How to build a plot composed by several subplots with a major axis.
  - One plot inside another

  Plots with color-maps:
  - using a z axis with `plt.scatter`
  - defining a colormap from scratch 
  
  Density plots using:
  - `mpl_scatter_density`
  - `plt.hist2d`

## `DistributionsHistograms` include examples of:

- how to plot histograms
- how to generate distributions of random numbers
    - Uniform 
    - Log-Uniform 
    - Gaussian `normal`
- violin plots
- boxplots
    
  
## `SaveRestoreData` include:
  How to save a restore data using:
  -  `np.save`
  -  `MacOSFile`
  - `np.savez`
  - `h5py`
  
## `readAndWriteFits` include:
  - how to read and write `*.fits` files with `astropy.io.fits` and `astropy.tables`
