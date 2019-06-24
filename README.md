# xarray_open_tutorial

Notebook and data for short xarray open tutorial presented at ICESat-2 Hackweek, Seattle, WA, 17 to 21 June, 2019.

The notebook contains a **very** short introduction to the python xarray package.  Please see 
http://xarray.pydata.org/en/stable/ for a more in depth introduction and documentation.

I've included an example of **vectorized indexing**, which, for example, could be used to extract values from gridded data
along an ICESat-2 track.  I've also included an example of how to interpolate an xarray field to a set of points.  The 
`segtrax` team use this to interpolate ice motion vectors to the locations of ICESat-2 sea ice freeboard segments.  The 
interpolation routine is based on one presented by Johan and Fernando Paolo.
