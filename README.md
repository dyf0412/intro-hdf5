Intro to HDF5 and ICESat-2 Data Files
-------------------------------------

Instructor: Fernando Paolo (paolofer@jpl.nasa.gov)  
Institution: NASA-JPL/Caltech

## Tutorials:  

Part 1: Introduction to HDF5 data model  
Part 2: Reduction of ICESat-2 data files  

## Goals:  

- Familiarize with HDF5 data model  
- Familiarize with HDF5 basic tools  
- Select IS2 files according region of interest  
- Extract variables of interest and filter in time and space  
- Prepare data for large-scale processing  
- Learn simple/generic data parallelization strategy  
- Inspect data files with plots (Histog, Maps, Time Series)  

## Libraries:    

- h5py (HDF5 handling)   
- numpy (numeric routines)  
- scipy (scientific routines)  
- pyproj (map projection routines)   
- joblib (shared-memory parallelization)  
- argparse (arguments parsing)  
- glob (pathname pattern expansion)  
- matplotlib (visualization routines)  
- getpass (password management)
- astropy (extra scientific routines)

## Credits

*The algorithms used in this tutorial are downscaled versions of a Python altimetry package, currently being devloped at JPL/Caltech, providing a range of algorithms for common tasks in altimetry data processing. It will soon become avalibale on GitHub as the `CapToolkit` for public usage.*
